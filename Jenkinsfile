pipeline {
  agent any
  stages {
    stage('Test/Shell Script') {
      steps {
        sh 'echo "I am Test"'
      }
    }

    stage('DEV') {
      steps {
        sh 'echo "I am "'
        echo 'I am in DEV'
      }
    }

    stage('PROD') {
      steps {
        echo 'I am in prod'
        echo 'Hi I am in Prod'
      }
    }

  }
}