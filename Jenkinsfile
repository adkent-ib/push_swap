pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "./Dockerfile && chmod +x Makefile && ./Makefile make all"
            }
        }
    }
}
