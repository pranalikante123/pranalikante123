pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }
        }
        stage('test') {
            steps {
                sh "systeminfo"
            }
        }
        stage('deploy') {
            steps {
                echo "testing pr build"
            }
        }
        stage('compile') {
            steps {
                echo "testing build"
            }
        }
    }
}
