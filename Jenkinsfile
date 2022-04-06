pipeline {
  agent any
  stages {
    stage('Setup Jenkins') {
      steps {
        sh 'ansible-playbook --vault-pass-file=.ansible_pass setup-jenkins.yml'
      }
    }
  }
}
