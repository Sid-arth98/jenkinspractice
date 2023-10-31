pipeline {
    agent any

    stages {
        stage('Hello'){
            agent { 
                docker {image 'node:16-alpine'}
            }
            steps {
                echo 'Hello World'
                sh 'node --version'
            }
        }
    
       stage('Helloo'){ 
            agent  { 
                docker {image 'node:16-alpine'}
            }
            steps {
                echo 'Hello00 World'
                sh 'node --version'
            }
        }
    }
}
