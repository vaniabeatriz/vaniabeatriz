pipeline{
  agent any
  options{
    timestamps()
    timeout(time 5, unit: 'MINUTES'
  }
  stages{
    stage("make directory"){
      options{
        retry(2)
      }
      steps{
        sh "mkdir ~/jenkins-tutorial-test"
      }
      
    }
    stage
    steps{
      sh "touch ~/jenkins-tutorial-test/file1.txt"
    }
  }
}
