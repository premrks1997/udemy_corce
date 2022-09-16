pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      steps {
        echo 'Buzz Buzz'
        echo 'hello'
        sh 'echo "this is prem" > file1.txt'
      }
    }

    stage('Archiveing') {
      steps {
        archiveArtifacts(artifacts: '**/*.txt', fingerprint: true)
      }
    }

  }
}