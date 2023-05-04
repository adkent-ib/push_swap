pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "export TERM=xterm; make ./push_swap"
            }
        }
    }
}
