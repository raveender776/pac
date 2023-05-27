def myfunc()
{
println "Here is my functions topics"
}

pipeline {
 agent any
 stages{
    stage("working with first stage")
    {
      steps{
        script{
         str="Hi am from"
         println "Here is your string Upper case:    ${str.toUpperCase()}"
         myfunc()
       }
      }
    }
  }
}
