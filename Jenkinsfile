pipeline {
    agent any
  
    tools {nodejs "NodeJS 16.0.0"}
  
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat 'cd .\coreui-template-code\'
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
