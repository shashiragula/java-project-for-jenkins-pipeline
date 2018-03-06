pipeline {
    agent any 
    stages {
        stage('SCM Checkout') {
 //           agent { docker 'maven:3-alpine' } 
            steps {
                echo 'SCM Checkout stage'
                sh 'java -version'
            }
        }
	stage('Build') {
 //           agent { docker 'maven:3-alpine' } 
            steps {
                echo 'Build Stage'
                sh ‘java -version'
            }
        }
        stage(‘Test') {
 //         agent { docker 'openjdk:8-jre' } 
            steps {
                echo ‘Test Stage’
                sh 'java -version'
            }
 	stage(‘Deploy’) {
//            agent { docker 'openjdk:8-jre' } 
            steps {
                echo ‘Deploy Stage’
                sh 'java -version'
            }

        }
    }
}

