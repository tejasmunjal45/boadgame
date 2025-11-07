pipeline {
    agent any
     
    
    stages {   
        stage('Compile') {
            steps {
            sh 'mv compile'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
