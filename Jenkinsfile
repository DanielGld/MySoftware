properties([pipelineTriggers([pollSCM('* * * * * ')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python file.py'
            }
        }
    }
}
