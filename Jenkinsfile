env.GITHUB_URL = 'https://github.com/paulojesousa/sample-java.git'
env.DOCKER_USERNAME = 'admin'
env.DOCKER_PASSWORD = 'admin'

node('docker') {

	stage('Clone') {
		sh "/stages/01_clone.sh"
	}
	
	stage('Build') {
		sh "/stages/02_build.sh"
	}
	
	stage('Test') {
		sh "/stages/03_test.sh"
	}
	
	stage('Archive') {
		sh "/stages/04_archive.sh"
	}
	
	stage('Deploy') {
		sh "/stages/05_deploy.sh"
	}
}
