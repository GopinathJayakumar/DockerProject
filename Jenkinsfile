pipeline {
  agent any
  stages {
    stage('Dev Evn') {
      steps {
        echo 'Dev Test to Starts'
        git(url: 'https://github.com/GopinathJayakumar/Sample', poll: true)
        powershell(script: 'mvnw package', label: 'Dev')
      }
    }

  }
}