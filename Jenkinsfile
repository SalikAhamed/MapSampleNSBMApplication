pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the app'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the app'
                script {
                  def test = 2 + 2 > 3 ? 'Cool' : 'not cool'
                  echo test
                }
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the app'
            }
        }  
    }
}
