pipeline {
 agent any
 environment {
  SUBJECT = "Jenkins-PAC"
}
parameters {
  choice choices: ['dev', 'sit ', 'pt ', 'prod'], description: 'Please choeese environment', name: 'ENV'
  string defaultValue: 'PAC', name: 'Subject'
}
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
