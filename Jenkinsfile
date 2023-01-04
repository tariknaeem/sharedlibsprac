@Library("shared-library")_

def myname = "Tarik"

pipeline {
  agent any
  stages{
    stage("UAT"){
      steps{
        sayHello "Tar"
        echo myname
     #   myname = "Naeem";
      
      }
    }
      stage("Map"){
        steps{
          mapExample(name:"test",dayOfweek:"Monday") 
          echo myname
        }
      
    
    }
       }
      }
     
    
