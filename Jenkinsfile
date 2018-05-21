pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                echo 'Building..'
                sh 'pwd'
                sh './gradlew build -x test'
            }
        }
        stage('build') {
            steps {
                sh './gradlew test'
            }
        }
    }
}