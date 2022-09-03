pipeline {
  agent any
  stages {
    stage('Run') {
      steps {
        bat "echo ${env.BRANCH_NAME}"
        bat "node index.js"
      }
    }
  }
}