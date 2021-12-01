pipeline {
	agent any
	stages{
		stage('Build') {
			steps {
				echo "123"
			}
		}
		stage('Test') {
			steps {
                sh "phpunit --log-junit results/phpunit/phpunit.xml git url:'https://github.com/marcuscai96/jenkins-phpunit-test/tree/main/tests'"
            		      }
			      }
	}
}
