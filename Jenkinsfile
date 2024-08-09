pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/your-username/your-repo-name.git'
                sh 'mvn clean package'
            }
        }
    }
}
