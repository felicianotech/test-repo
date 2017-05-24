pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'Building..'
            }
        }
        stage('Test'){
            steps {
                grep "chicken" Jenkinsfile
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
