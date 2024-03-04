pipeline {
    agent any

        tools {
        // Define Node.js tool named 'NodeJS'
        nodejs 'Node'
        }

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from your version control system
                git 'https://github.com/KoushaliyaSree/Practice1.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                // Install Node.js dependencies using npm
                sh 'npm install'
            }//Hello
        }

        stage('Build') {
            steps {
                // Build your Node.js application (if needed)
                sh 'npm run build'
            }
        }

        stage('Test') {
            steps {
                // Run tests for your Node.js application
                sh 'npm test'
            }
        }

    }
}
