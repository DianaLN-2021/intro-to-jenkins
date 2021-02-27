pipeline {
    agent { 
        label 'docker'
    }
    stages {
        stage('build') {
            docker { image 'maven:3.3.3' }
            steps {
                sh 'mvn --version'
            }
        }
    }
}
