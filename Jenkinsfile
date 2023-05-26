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
         StringValue = "Hello Edpresso"
         println "here is your string reverse${StringValue.reverse()}"
         println "here is my current build result ${currentBuild.result},${currentBuild.id}"
         println "Here is your envirnment varibles ${env.SUBJECT}"
         println "Here is your parameter value ${params.Subject},${params.ENV}"
        }        
      }
    }
  }
}
