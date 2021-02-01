pipeline {
  agent any
  stages {
    stage('CKout') {
      steps {
        sh 'rm -rf DockerAndroidDemo'
        sh 'git clone https://github.com/successanil/DockerAndroidDemo.git --no-checkout'
        sh '''cd DockerAndroidDemo
'''
        sh 'git sparse-checkout init --cone'
        sh 'git sparse-checkout set DockerAndroidDemoProject'
      }
    }

  }
}