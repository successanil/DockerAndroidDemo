pipeline {
  agent any
  stages {
    stage('CKout') {
      steps {
        sh '''git clone https://github.com/successanil/DockerAndroidDemo.git --no-checkout
cd DockerAndroidDemo
git sparse-checkout init --cone
git sparse-checkout set DockerAndroidDemoProject'''
      }
    }

  }
}