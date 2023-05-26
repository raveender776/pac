pipeline {
 agent any
 environment {
  SUBJECT = "Jenkins-PAC"
}
  stages{
    stage("working with first stage")
    {
      steps{
        script{
         StringValue = "Hello Edpresso"
         println "here is your string reverse${StringValue.reverse()}"
         println "here is my current build result ${currentBuild.result},${currentBuild.id}"
         println "Here is your envirnment varibles ${env.SUBJECT}"
        }        
      }
    }
  }
}
