pipeline {
    agent any
    tools {
        maven "Maven 3.8.6" 
    }
    stages {
        stage('Clean and Install') {
            steps {
               sh 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
               sh 'mvn package'
            }
        } 
    }
}
