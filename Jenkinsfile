pipeline {
  agent any
  tools {
    maven 'Apache Maven 3.5.2'
  }

  stages {
    stage('Build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}
