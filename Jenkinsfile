@Library("shared-library")_

def myname = "Tarik"

pipeline {
  agent any
  stages{
    stage("UAT"){
      steps{
        script{
          sayHello "Tar"
        echo myname
        myname = "Naeem"
        }
      }
    }
      stage("Map"){
        steps{
          script{
            
            mapExample(name:"test",dayOfweek:"Monday") 
            echo myname
        }
        }
    
    }
       }
      }
     
    
