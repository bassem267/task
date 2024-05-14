pipeline {
    agent any

    stages {
        stage ('Test'){
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('Build') {
            steps {
                // Ensure correct path separator for Windows
                bat 'bash.sh'
            }
        }
    }
}
