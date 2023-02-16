pipeline{
  agent any
  stages{
    stage("built"){
      steps{
        sh'./hi.sh'
      }
    }
    stage("last process update"){
      steps{
       echo "build in process and completed"
      }
    }
    stage("test"){
      steps{
        echo "running test"
      }
    }
  }
}






