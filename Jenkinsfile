pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the repository
                git url: 'https://github.com/binitapatel164/ecommerce', branch: 'main'
            }
        }
        age('Build and Test') {
            steps {
                //tool name: 'Nodejs', type: 'nodejs'
       //         sh "${npmhome}/bin/npm install"          // Install project dependencies
         //       sh "${npmhome}/bin/npm run build"        // Build the React project
           //     sh  "${npmhome}/bin/npm test"             // Run tests if applicable
       sh 'npm install'          // Install project dependencies
                sh 'npm run build'        // Build the React project
                sh  'npm test'             // Run tests if applicable
            }
        }
    }
}
