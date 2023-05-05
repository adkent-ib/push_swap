pipeline {
    agent any
    stages {
        stage('Install make')
        {
            steps {
                sh "apt-get install make -y"
            }
        }
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
