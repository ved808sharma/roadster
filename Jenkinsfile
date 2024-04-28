pipeline {
    agent any

    stages {
        stage('Build & Unit Test') {
            steps {
                sh 'mvn clean verify'
            }
        }
        stage('Code Scan') {
            steps {
                echo 'Scanning the code using sonar qube..'
            }
        }
        stage('Image build') {
            steps {
                echo 'building the image....'
            }
        }
        stage('Image Scan') {
            steps {
                echo 'building the image....'
            }
        }
        stage('Image Push') {
            steps {
                echo 'building the image....'
            }
        }
    }
}