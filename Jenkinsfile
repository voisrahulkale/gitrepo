pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -f gitrepo/javademos-master/ssgsems/pom.xml -B -DskipTests clean package'
      }
    }

  }
}