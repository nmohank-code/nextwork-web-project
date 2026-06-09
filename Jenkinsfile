pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning code from GitHub...'
                git branch: 'master', url: 'https://github.com/nmohank-code/nextwork-web-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
                sh 'echo Build step executed'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Test step executed'
            }
        }
    }
}
