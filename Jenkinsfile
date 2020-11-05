env.GITHUB_URL = 'https://github.com/paulojesousa/sample-java.git'
node('docker') {

echo $env.GITHUB_URL

	stage('Clone') {
		sh "/stages/01_clone.sh"
	}
	
	stage('Build') {
		sh "/stages/02_build.sh"
	}
}
