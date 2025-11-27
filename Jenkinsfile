pipeline {
    agent any

    stages {
        stage('Clone') {
            steps { git url: 'https://github.com/mhassini/avec-maven.git' }
        }
        stage('Build') {
            steps { sh 'mvn -version' }
        }
        stage('Hello') {
            steps { echo "Pipeline using Jenkinsfile" }
        }
    }
}
