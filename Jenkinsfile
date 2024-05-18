pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/bassem267/task-bouns', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                script {
                    dir('C:/ProgramData/Jenkins/.jenkins/workspace/Jenkins Task') {
                        bat 'dir2.bat'
                    }
                }
            }
        }
    }
}
