pipeline {
	agent {
		dockerfile{
			filename 'Dockerfile'
		}	
	}
	stages {
		stage('Prueba') {
			steps {
				sh 'uname -a'
				sh 'echo hola'
			}
		}	
	}
}
