pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Build'               
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Sonarqube') {
            steps {
                echo 'Sonarqube'
            }
        }
        stage('Push to artifactory') {
            steps {
                echo 'Push to artifactory'
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
      always {
        echo 'always'
      }
    }
}