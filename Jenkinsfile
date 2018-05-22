node {
    stage('CheckOut') {
        checkout scm
        echo 'Check Out Stage'
        bat './gradlew clean'
    }
    stage('Build') {
      echo 'Build Stage'
      bat './gradlew build'
    }
    stage('Test') {
        echo 'Test Stage'
        bat './gradlew test'
    }
}