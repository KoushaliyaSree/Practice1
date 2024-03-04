pipeline {
    agent any

        tools {
        // Define Node.js tool named 'NodeJS'
        nodejs 'Node'
        }

    stages {
      
   

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
