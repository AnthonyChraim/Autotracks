pipeline {
    agent any
  
    tools {nodejs "Node 14.8.1"}
  
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat """
                    cd coreui-template-code
                    npm install --legacy-peer-deps
                    """.stripIndent().trim()
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
