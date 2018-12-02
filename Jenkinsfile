pipeline
{
 agent any
 
 stage ('compile stage') 
   {
     steps 
        {
            withMaven (maven : 'apache-maven-3.5.4') 
             {
                sh 'mvn clean compile' 
             }
        }
   }
}
