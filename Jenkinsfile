pipeline {
    agent any
      tools {
        maven 'Maven-Auto'   // Name from Global Tool Configuration
        jdk 'JDK-17'         // Optional: auto-install JDK
    }
    
    stages {   
        stage('Compile') {
            steps {
            sh 'mvn compile'
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
