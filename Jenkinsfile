node('jdk11-mvn3.8.4')) {
  
  stage('source') {
    git 'https://github.com/ameervali/java11-examples.git'
  }
  
    stage('build') {
        sh '''
            echo "PATH=${PATH}"
            echo "M2_HOME=${M2_HOME}"

        '''
        sh '/usr/local/apache-maven-3.8.4/bin/mvn clean package'
    }
  
}
