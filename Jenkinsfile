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
                sh "./vendor/bin/phpunit --log-junit logs/unitreport.xml -c git url:'https://github.com/marcuscai96/jenkins-phpunit-test/blob/main/tests/phpunit.xml' tests"
            		      }
			      }
	}

}
