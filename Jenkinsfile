pipeline {
  agent any
    stages {
      stage('Build') {
        steps {
	  sh 'printenv'
	  sh echo 'hi'
	      }
	steps {
	  sh 'ant -f build.xml -v'
	      }
	}
  }	
}
