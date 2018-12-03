node {

stage("checkout")
  {
    
   git "https://github.com/madhuyellanur/SampleApplication.git/"
  }
  
stage("compile")
  {
  def mvnHOME = tool name: 'apache-maven-3.5.4', type: 'maven'
    sh ="${mvnHOME}/bin/mvn package"
}
  
}
