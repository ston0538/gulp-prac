pipeline {
  agent {
    docker {
      image "node:6-alpine"
      args "-p 3000:3000"
    }
  }
  stage("build") {
    steps {
      sh "npm install"
    }
  }
}