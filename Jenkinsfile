node{
	stage('Git Checkout'){
		git 'https://github.com/sherlocksecurity/Pipeline_Private'
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
}
