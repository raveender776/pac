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
         for (j=0; j<=10;j++)
         {
          println "${j}"
         }  
         for (k in [20,30,40,50])
         {
          print "here is your k value:  ${k}"
         }
         for (l in 30..40)
         {
          print "here is your l value:  ${l}"
         }
         }
      }
    }
  }
}
