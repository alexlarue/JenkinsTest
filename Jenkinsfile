#!groovy
// Alex Test 11-12 1:32pm
// a simple pipeline
def pipeline = {
  node {
    stage('install') {
      sh 'echo installing'
    }

    stage('build') {
      sh 'echo build'
    }

    stage('test'){
      sh 'echo test'
    }
    
    stage('deploy') {
      sh 'echo deploy'
    }
  }
}

pipeline()
