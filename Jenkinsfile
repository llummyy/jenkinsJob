pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'using mavrren to build code'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'running JUnit integration tests'
            }
        }
      
        stage('Code Analysis') {
            steps {
                echo 'SOnarQube analuysing the code'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'checking  vvvulnerabilities using OWASP'
            }
        }

      
        stage('Deploy to Staging') {
            steps {
                echo 'deploying to the server AWS EC2'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'usinnng selenium to run integration test'
            }
        }

      
        stage('Deploy to Production') {
            steps {
                echo 'Deployingapplication to production server AWS'
            }
        }
    }
}

