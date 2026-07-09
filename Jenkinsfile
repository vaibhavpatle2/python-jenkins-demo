pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/vaibhavpatle2/python-jenkins-demo.git'
            }
        }

        stage('Run Python') {
            steps {
                bat 'python hello.py'
            }
        }
    }
}
