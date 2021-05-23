pipeline {
    agent any
    stages {
        stage('code pull') {
            steps {
                git 'https://github.com/javaparser/javaparser-maven-sample.git'
            }
        }
        stage ('build') {
            steps {
                mvn install
            }
        }
    }
}
