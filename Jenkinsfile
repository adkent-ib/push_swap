pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "export TERM=xterm; ./Makefile all"
            }
        }
    }
}
