pipeline {
  agent any
  tools {
    maven "maven3.9.6"
  }

  stages {
    stage ("Git clone") {
      steps {
        git branch: 'main', url: 'https://github.com/Obuorgithub/web-app-devops.git'
    }
  }
}