pipeline {
	agent any {
		docker {
			image 'composer:latest'
		}
	}
	stages {
		stage('Build') {
			steps {
				sh 'composer install'
			}
		}
		stage('Test') {
			steps {
                sh '/usr/bin/phpunit tests'
            }
		}
	}
}
