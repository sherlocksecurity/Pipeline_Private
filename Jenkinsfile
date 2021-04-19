node{
	stage('Git Checkout'){
		git 'https://github.com/sherlocksecurity/Pipeline_Private'
	}
	stage('Compile-Package'){
		//Maven home path
		def mvnHome = tool name: 'maven 3.3.9', type: 'maven'
		sh "${mvnHome}/bin/mvn package"
	}
}
