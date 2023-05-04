pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "apt-get update -y && chmod +x Dockerfile && ./Dockerfile && chmod +x Makefile && ./Makefile make all"
            }
        }
    }
}
