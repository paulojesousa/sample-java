env.GITHUB_URL = 'https://github.com/paulojesousa/sample-java.git'
node('docker') {

	stage('Clone') {
		sh "/stages/01_clone.sh"
	}
	
	stage('Build') {
		sh "/stages/02_build.sh"
	}
}
