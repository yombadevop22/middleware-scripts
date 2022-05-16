pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sleep 5
            }
        }
         stage('build') {
            steps {
                echo 'build'
                sleep 4
            }
        }
         stage('test') {
            steps {
                echo 'test'
                sleep 5
            }
        }
         stage('deploy') {
            steps {
                echo 'deploy'
                sleep 5
            }
        }
    }
}
