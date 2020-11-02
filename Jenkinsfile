node('docker') {

    stage('Checkout') {
        checkout scm
	}
    stage('Build') {
		sh "/stages/02_build.sh"
	}
}
