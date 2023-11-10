pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/Kasukurthi-Srinivas014/Test.git'
            }
        }
        stage('build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}
