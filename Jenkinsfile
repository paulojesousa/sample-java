node('docker') {

    stage 'Clone'
		sh "/stages/01_clone.sh"
		
	stage 'Build'
		sh "/stages/02_build.sh"

	stage 'Test'
		sh "/stages/03_test.sh"

	stage 'Archive'
		sh "/stages/04_archive.sh"
}
