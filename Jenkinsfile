pipeline {
    agent any

    stages {
        stage('jmeter test') {
            steps {
              sh "mvn verify -Pperformance"
            }
        }

    }
}
