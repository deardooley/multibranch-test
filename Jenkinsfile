node() {
  stage 'Checkout'
  checkout scm: [$class: 'GitSCM', branches: [[name: '*/${GIT_BRANCH}']], userRemoteConfigs: [[url: '${GIT_URL}']]]

	stage 'Setup'
		showenv();

  stage 'Build'
  	sh('env');

}


def showenv() {
	def env = System.getenv()

	env.each {
		println it
	}

}

