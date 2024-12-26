pipeline{
  agent any
  stages{
    stage('Built'){
      steps{
        echo "i am building"
      }
    }
    stage('test'){
      steps{
        echo "i am testing"
      }
    }
    stage('Deploy'){
      steps{
        echo "Deploying"
      }
    }
    post{
      success{
        echo "Your pipeline is success"
      }
      failure{
        echo "pipeline failed"
      }
    }
}
