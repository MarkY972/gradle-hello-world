pipeline {
    agent slave1
    stages {
        stage ('checkout'){
            steps {
                sh git clone https://github.com/MarkY972/gradle-hello-world.git
            }
        }
        stage('build') {
            steps { 
                sh "build.gradle"
            }
        }
    }
}
