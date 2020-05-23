
pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'PATH=/home/sriharsha/Desktop/8th_sem/SPE/project:$PATH selenium-side-runner OnlineNotesSharing.side -c "browserName=chrome goog:chromeOptions.args=[headless]" --output-directory=results --output-format=junit'
      }
    }
  }
}
