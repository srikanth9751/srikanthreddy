pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                git 'https://github.com/javaparser/javaparser-maven-sample.git'
            }
        }
        stage ('quality') {
            steps {
                sh 'echo "in deploy stage" '
            }
        }
    }
}
