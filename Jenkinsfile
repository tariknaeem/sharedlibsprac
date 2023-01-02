@Library("shared-library")_

pipeline {
  agent none
  stages{
    stage("start"){
      steps{
        script{
          sayHello
        }
        }
    }
    stage("UAT"){
      steps{
        Script{
        mapExample(name:"Tarik", dayOfweek:"Monday")
        }
        }
       }
      }
     } 
    
