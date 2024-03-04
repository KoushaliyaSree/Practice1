pipeline {
    agent any

        tools {
        // Define Node.js tool named 'NodeJS'
        nodejs 'node'
        }

    stages {
       stage('Checkout') {
            steps {
                // Checkout the code from your version control system
                git branch: 'main', url: 'https://github.com/KoushaliyaSree/Practice1.git'
            }
        }
   
      stage('Install Dependencies') {
            steps {
                // Install Node.js dependencies using npm
                sh 'npm install'
            }
        }

        stage('build') {
            steps {
                // Build your Node.js application (if needed)
               sh 'npm start'
            }
        }

        stage('Test') {
            steps {
                // Run tests for your Node.js application
                echo 
            }
        }

    }
}
