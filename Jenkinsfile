pipeline {
    agent any
    stages {
        stage('Install dependencies')
        {
            steps {
                sh "./Makefile all"
            }
        }
    }
}
