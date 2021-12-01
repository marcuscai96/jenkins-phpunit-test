pipeline {
	agent any
		stage('Build') {
			steps {
				echo "123"
			}
		}
		stage('Test') {
			steps {
                phpunit --log-junit results/phpunit/phpunit.xml git url:'https://github.com/marcuscai96/jenkins-phpunit-test/tree/main/tests'
            }
		}
	}
}
