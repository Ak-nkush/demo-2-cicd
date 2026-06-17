pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                echo 'Building your application...'
                sh 'echo "Insert build commands here (e.g., npm run build, mvn package)"'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing your application...'
                sh 'echo "Insert test commands here (e.g., npm test, pytest)"'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying your application...'
                sh 'echo "Insert deployment commands here"'
            }
        }
    }
}