def myfunc(int a, int b)
{
 result = a + b
 println "Here is my your ${a} value: ,and Here is your ${b} value:,${result}"
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
         myfunc(10,20)
         myfunc(30,40)
       }
      }
    }
  }
}
