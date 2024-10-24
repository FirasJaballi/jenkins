pipeline {
    agent any
    tools {
        maven "MVN_3.8.7"
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Maven') {
            steps {
                sh "mvn --version"
            }
        }
    }
}
