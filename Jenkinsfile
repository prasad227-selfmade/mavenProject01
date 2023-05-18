pipeline {
    agent any

    stages {
        stage('Docker') {
            steps {
                echo 'Hello-Docker-Stage'
                build quietPeriod: 5, job: 'Tomcat-Docker'
            }
        }
           
        stage('Linux') {
            steps {
                echo 'Hello-Linux-Stage'
                build quietPeriod: 5, job: 'Tomcat-Linux'
            }
        }

        stage('AWS') {
            steps {
                echo 'Hello-AWS-Stage'
                build quietPeriod: 5, job: 'Tomcat-AWS'
            }
        }
    }
}
