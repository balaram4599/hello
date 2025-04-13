pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/balaram4599/hello.git', branch: 'main'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -la'
                sh 'python3 hello.py'
            }
        }
        
    }
}
