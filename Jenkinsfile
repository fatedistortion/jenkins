pipeline {
    agent any 
    stages {
        stage('Stage 0') {
            steps {
                echo 'Hello cha!'
            }
        }
        stage('Stage 1') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JAVA_HOME}"
            }
        }
    }
}