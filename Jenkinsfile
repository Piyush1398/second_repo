pipeline{
  agent any
  stages{
    stage("permission"){
      steps{
        sh'./hi.sh'
      }
    }
    stage("build"){
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






