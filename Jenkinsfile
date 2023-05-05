pipeline {
    agent any
    stages {
        stage('Install dependencies and push swap')
        {
            steps {
                sh "chmod +x ./Makefile && export TERM=xterm; make"
            }
        }
        stage('Install dependencies and checker')
        {
            steps {
                sh "chmod +x ./Makefile && export TERM=xterm; make"
            }
        }
    }
}
