pipeline{
  
  agent none
   stages{
    stage("built"){
      steps{
        bash'./hi.sh'
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






