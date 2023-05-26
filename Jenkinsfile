pipeline {
 agent any
 stages{
    stage("working with first stage")
    {
      steps{
        script{
         var = 1
         while (var <= 10)
         {
         println "Here is your var value :  ${var}"
          var = var+1
         }
        }        
      }
    }
  }
}
