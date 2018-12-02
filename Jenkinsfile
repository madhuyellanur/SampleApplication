pipeline
{
 agent sample 
{
stages("compile stage")
 {
  steps
  {
  withMaven (maven : 'apache-maven-3.5.4')
   sh 'mvn clean compile' 
 }
 }
 stage("Test Stage")
 {
   steps
     {
      withMaven (maven : 'apache-maven-3.5.4')
      sh 'mvn test' 
     }
  }
}
}
