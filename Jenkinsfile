node {
  def mavenHome = tool name: "maven3.9.0"
  
  stage('source') {
    git 'https://github.com/ameervali/java11-examples.git'
  }
  
  stage('build') {
    sh "$(mavenHome}/bin/mvn clean package"
  }
  
}
