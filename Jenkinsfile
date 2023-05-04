pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "chmod +x Dockerfile && ./Dockerfile && chmod +x Makefile && ./Makefile make all"
            }
        }
    }
}
