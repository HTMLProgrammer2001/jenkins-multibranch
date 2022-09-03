pipeline {
  agent any
  stages {
    stage('Run') {
      bat "echo ${env.BRANCH_NAME}"
      bat "node index.js"
    }
  }
}