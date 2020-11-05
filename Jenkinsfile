node('docker') {

	def GITHUB_URL  = 'https://github.com/paulojesousa/sample-java.git'

	stage('Clone') {
		sh "/stages/01_clone.sh"
	}
	
	stage('Build') {
		sh "/stages/02_build.sh"
	}
}
