pipeline {
 agent any
  stages{
    stage("working with first stage")
    {
      steps{
        script{
         StringValue = "Hello Edpresso"
         println "here is your string reverse${StringValue.reverse()"}
        }        
      }
    }
  }
}
