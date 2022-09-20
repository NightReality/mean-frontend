pipeline {
  agent any
  stages {
    stage('Clone Repo') {
      steps {
        git(branch: 'main', url: 'https://github.com/NightReality/mean-frontend')
      }
    }

    stage('la') {
      steps {
        sh 'la'
      }
    }

  }
}