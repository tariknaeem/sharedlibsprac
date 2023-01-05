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
    stage("Example usrname and password"){
      environment{
        SERVICE_CREDS = credentials('my-username-pass')
      }
      steps{
        sh 'echo "service user is $SERVICE_CREDS_USR"'
        sh "service user is $SERVICE_CREDS_PSW"
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
     
    
