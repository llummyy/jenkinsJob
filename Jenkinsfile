pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'usinnnnng mavrren to build code'
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
                echo 'checking  vvulnerabilities using OWASP'
            }
        }

      
        stage('Deploy to Staging') {
            steps {
                echo 'deploying to server AWS EC2'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'using selenium to run integration test'
            }
        }

      
        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to production server AWS'
            }
        }
    }
}

