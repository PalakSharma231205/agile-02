pipeline {
    agent any 

    stages {
        stage('Hello') {
            steps {
                echo 'Hello, Jenkins! This is my first pipeline.'
            }
        }
        stage('Check Environment') {
            steps {
                // We use "env.VARIABLE_NAME" to access Jenkins environment info
                echo "Running on Jenkins version: ${env.JENKINS_VERSION}"
                echo "Job Name: ${env.JOB_NAME}"
            }
        }
    }
}
