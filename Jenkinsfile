pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "chmod +x Makefile && export TERM=xterm; make all"
            }
        }
    }
}
