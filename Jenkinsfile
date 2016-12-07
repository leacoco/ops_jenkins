node {
	stage 'Build and Test'
	env.PATH = "${tool 'DevMAVEN'}/bin:${env.PATH}"
	git url: "http://github.com/leacoco/ops_jenkins.git"
	bat 'mvn clean package'
}