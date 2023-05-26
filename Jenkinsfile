pipeline {
 agent any
  stages{
    stage("working with first stage")
    {
      steps{
        script{
         class Main {
             static void main(String[] args) {
              String value = "Hello Edpresso";
              println(value.reverse());
           } 
         }
        }
      }
    }
  }
}
