pipeline {
  
  agent any
  
  stages {
    stage('build image') {
      steps {
        script{
          sh 'sudo docker build -t naveed0004/angular:${BUILD_NUMBER} -f angular-client/Dockerfile /angular-client '
        } 
      }
    }
  }
}
