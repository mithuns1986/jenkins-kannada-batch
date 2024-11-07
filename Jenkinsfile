pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Running on BUILD # ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Example 2') {
            steps {
                echo "This is triggered by webhook"
            }
        }
    }
}
