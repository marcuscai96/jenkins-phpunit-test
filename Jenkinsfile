pipeline {
	agent any 
	stages {
		stage('Build') {
			steps {
				echo '1234'
			}
		}
		stage('Test') {
			steps {
                sh '/usr/bin/phpunit test'
            }
		}
	}
}
