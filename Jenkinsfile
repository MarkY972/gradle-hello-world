pipeline {
    agent slave1
    stages {
        stage ('checkout'){
            steps {
                sh https://github.com/MarkY972/gradle-hello-world.git
            }
        }
        stage('biuld') {
            steps {
                sh "whoami"
            }
        }
    }
}
