pipeline {
    agent any
    stages {
        stage('Install dependencies and push swap')
        {
            steps {
                sh "TERM=xterm make clean all re"
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
