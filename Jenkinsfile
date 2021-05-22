pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "in build stage"'
            }
        }
        stage ('quality') {
            steps {
                sh 'echo "in deploy stage" '
            }
        }
    }
}
