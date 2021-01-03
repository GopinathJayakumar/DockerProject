pipeline {
  agent any
  stages {
    stage('Dev Evn') {
      steps {
        echo 'Dev Test to Starts'
        git(url: 'https://github.com/GopinathJayakumar/Sample', poll: true)
        bat(script: 'mvn install', label: 'Dev')
      }
    }

  }
}