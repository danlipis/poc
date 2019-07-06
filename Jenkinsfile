pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'Teste'
      }
    }
    stage('Send email') {
      steps {
        mail(subject: 'Teste deploy', body: 'lalalal', from: 'danlipis@gmail.com', to: 'daniel.bastos@gmail.com')
      }
    }
  }
}