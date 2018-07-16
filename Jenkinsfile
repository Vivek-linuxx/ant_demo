pipeline {
	agent any
	
	stages {
		stage('build') {
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
