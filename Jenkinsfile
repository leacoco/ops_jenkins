node {
	stage 'Build and Test'
	env.PATH = "${tool 'Maven 3'}/bin:${env.PATH}"
	git url: "http://github.com/leacoco/ops_jenkins.git"
	sh 'mvn clean package'
}