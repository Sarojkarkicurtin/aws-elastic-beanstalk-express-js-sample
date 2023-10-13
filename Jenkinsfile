pipeline {
    agent {
        docker {
            image 'node:16' // Use Node 16 Docker image
        }
    }
   
    stages {
        stage('Build') {
            steps {
                sh 'npm install --save' // Run npm install
            }
        }
       
        // Add more stages as needed for your CI/CD process
    }
   
    post {
        always {
            // Clean up or perform other post-build actions if necessary
        }
    }
