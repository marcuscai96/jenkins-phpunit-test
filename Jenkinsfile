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
                phpunit --log-junit results/phpunit/phpunit.xml -c test/phpunit.xml
            }
		}
	}
}
