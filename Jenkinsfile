pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "echo Hello && chmod +x Makefile && export TERM=xterm; make fclean"
            }
        }
    }
}
