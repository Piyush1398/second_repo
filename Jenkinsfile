pipeline{
  agent any
  stages{
    stage("permission"){
      steps{
         sh "ls"
      }
    }
    stage("build"){
      steps{
        sh 'bash hi'
      }
    }
    stage("test"){
      steps{
        echo "running test"
      }
    }
  }
}






