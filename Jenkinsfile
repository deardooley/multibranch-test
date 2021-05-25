node() {
  stage 'Checkout'

	stage 'Setup'
		showenv();

	stage 'Checkout'
		checkout scm

  stage 'Build'
  	sh('env');

}


def showenv() {
	def env = System.getenv()

	env.each {
		println it
	}

}

