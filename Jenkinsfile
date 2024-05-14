pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'chmod +x bash.sh'
                sh './bash.sh'
            }
        }
    }
}
