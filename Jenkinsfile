pipeline {
	agent	any
	stages{
		stage('Build'){
			steps{
			sh '/opt/apache-maven-3.6.1/bin/mvn clean package'
			}
		}
	}
}
