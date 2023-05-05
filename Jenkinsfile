pipeline {
    agent any
    stages {
        stage('Install dependencies and push swap')
        {
            steps {
                sh "TERM=xterm make clean && make push_swap"
            }
        }
        stage('Install dependencies and checker')
        {
            steps {
                sh "TERM=xterm make checker"
            }
        }
    }
}
