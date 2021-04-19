node{
	stage('Git Checkout'){
		git 'https://github.com/sherlocksecurity/Pipeline_Private.git'
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
}
