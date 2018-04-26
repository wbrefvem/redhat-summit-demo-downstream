pipeline {
  agent any
  stages {
    stage('Received Notification') {
      steps {
        echo 'World says Hello, we say Hi!'
      }
    }
  }
  triggers {
    eventTrigger(simpleMatch('helloWorld'))
  }
}