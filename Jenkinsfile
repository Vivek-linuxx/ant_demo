pipeline {
  agent any
  stages {
      stage('Build') {
          steps {
	      sh 'printenv'
	      sh echo 'hi'
	      sh 'ant -f build.xml -v'
	      }
	}
  }	
}
