pipeline {
    agent any
     tools { 
        maven 'maven-3.6.0' 
       // jdk 'jdk8' 
    }
    stages {
        stage('Build & Unit Test') {
            steps {
                sh 'java --version'
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