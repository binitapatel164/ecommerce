pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the repository
                git url: 'https://github.com/binitapatel164/ecommerce.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                // Perform build steps here
                // For PHP, you might run commands like composer install or any other necessary build steps
                git url: 'https://github.com/binitapatel164/ecommerce.git', branch: 'main'
                
            }
        }

        stage('Test') {
            steps {
                // Run PHPUnit tests for test123.php
                git url: 'https://github.com/binitapatel164/ecommerce.git', branch: 'main'
                
            }
        }
    }
}
