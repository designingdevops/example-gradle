pipeline {
  agent {
    docker {
      image "gradle"
      label "docker"
    }
  }
  stages {
    stage ('build') {
      steps {
        sh "./gradlew build"
      }
    }
  }
}
