pipeline {
  agent any
 
  tools {nodejs "node"}
 
  stages {
    stage('Example') {
      steps {
        sh 'npm install'
	sh './script/test' 
      }
    }
  }
}
