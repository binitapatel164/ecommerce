pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the repository
                git url: 'https://github.com/binitapatel164/ecommerce', branch: 'main'
            }
        }

        stage('Test') {
            steps {
                sh 'phpunit DatabaseConnectionTest.php'
            }
        }




    }
}
