@Library("Shared_Libraries") _ 
pipeline {
    agent any 
    stages {
        stage('Maven') { 
            steps {
                sh 'echo "Funciona Maven"'
                Maven()
                // 
            }
        }
        stage('Gradle') { 
            steps {
                sh 'echo "Funciona Gradle"'
                Gradle()
                // 
            }
        }   
    }
}