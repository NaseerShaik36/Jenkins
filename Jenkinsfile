pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Hi') {
            steps {
                echo 'Hello word2'
            }
        }
        stage('environment') {
            steps {
                echo env.BUILD_ID
                echo env.JENKINS_HOME
                echo env.JOB_NAME
            }
        }
    }
}

