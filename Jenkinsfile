pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "123"
			}
		}
		stage('Test') {
			steps {
                sh './vendor/bin/phpunit tests'
            }
		}
	}
}
