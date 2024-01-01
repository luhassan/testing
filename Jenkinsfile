pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello, Jenkins!'
                echo 'Flushing output...'
                script {
                    currentBuild.rawBuild.getLogFile().flush()
                }
            }
        }
    }
}
