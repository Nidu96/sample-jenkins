pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', credentialsId: 'nidu', url: 'https://github.com/Nidu96/AgroLink-Angular-Node.git'
            }
        }
        stage('Build') {
            steps {
                sh 'ls'
                sh 'pwd'
            }
        }
    }
}
