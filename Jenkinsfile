pipeline {
    agent any
    
    environment {
        GIT_URL = 'https://github.com/kenkool23/MyProject.git'
        TOMCAT_URL    = 'http://54.91.213.14:8080/'
    }
    
    stages {
        stage('Git Checkout') {
            steps {
                git "${GIT_URL}"
            }
        }
        stage('Second Stage') {
            steps {
                sh 'echo this is the second stage Dev'
            }
        }
      }
    }
