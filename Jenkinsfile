pipeline{
  agent any
  stages{
    stage('checkout'){
      step{
        echo "commiting to github"
      }
    }
    stage('build'){
      step{
        echo "building the project"
      }
    }
    stage("deploying"){
      step{
        echo "deploying...."
      }
    }
  }
}
