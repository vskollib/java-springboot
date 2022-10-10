pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Building'             
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy to QA') {
            steps {
                echo 'Deploy to QA'
            }
        }

        stage('Deploy to Prod') {
            steps {
                echo 'Deploy to Prod'
            }
        }
    }
    post {
      failure {
        echo 'Failed'
      }
      success {
        echo 'Success'
      }
      aborted {
        echo 'aborted'
      }
    }
}