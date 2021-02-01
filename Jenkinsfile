pipeline {
  agent any
  stages {
    stage('CKout') {
      steps {
        sh '''rm -rf DockerAndroidDemo
git clone https://github.com/successanil/DockerAndroidDemo.git --no-checkout
cd DockerAndroidDemo
git sparse-checkout init --cone
git sparse-checkout set DockerAndroidDemoProject'''
      }
    }

  }
}