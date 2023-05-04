pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "docker exec -ti --user root /bin/bash && apt-get update -y && chmod +x Dockerfile && ./Dockerfile && chmod +x Makefile && ./Makefile make all"
            }
        }
    }
}
