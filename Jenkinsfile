pipeline{
  agent any
  stages{
    stage("permission"){
      steps{
        sh "chmod +x hi.sh"
        sh "ls"
      }
    }
    stage("build"){
      steps{
        sh 'bash hi.sh'
      }
    }
    stage("test"){
      steps{
        echo "running test"
      }
    }
  }







