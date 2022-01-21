pipeline {
    agent { label "java" }

    stages {
        stage("checkout"){
            steps {
                checkout scm
            }
        }

        stage("build java app"){
            steps {
                sh "docker-compose build"
            }
        }
}
