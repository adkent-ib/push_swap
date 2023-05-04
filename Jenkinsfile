pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "chmod +x Makefile && ./Makefile make all"
            }
        }
    }
}
