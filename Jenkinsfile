pipeline{
  agent any
  triggers {
        githubPush()
    }
  stages{
    stage("build"){
      steps{
          echo "building app"
      }
    }
    stage("test"){
      steps{
      echo "testing"
      }
    }
    stage("deploy"){
      steps{
    
      echo "deploying"
      }
    }
  }
}
