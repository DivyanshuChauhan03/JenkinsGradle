pipeline{
	agent any
	
	tools{
		gradle 'Gradle'
		jdk 'JDK'
	}
	stages{
		stage('checkout'){
		steps{
		git branch : 'main' , url : 'https://github.com/DivyanshuChauhan03/JenkinsGradle'
		}
		}
		
		stage('build'){
		steps{
		sh 'gradle build'
		}
		}
		stage('run'){
		steps{
		sh 'gradle run'
		}
		}
	}
		
}
		
