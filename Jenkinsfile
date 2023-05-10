pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'Hello-Dev-Stage'
                build quietPeriod: 5, job: 'Tomcat-Docker'
            }
        }
    }
}
