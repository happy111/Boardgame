pipeline {
    agent any

    
    tools {
        jdk 'jdk17'
        maven 'Maven3'
    }

    stages {   
        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
        

        
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
