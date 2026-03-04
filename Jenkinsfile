
pipeline{
    agent any
    
    stages{
        stage('Build'){
		steps{
			bat 'mvn package'
			}
		}
		stage('Run'){
			steps{
				bat 'java-java/1.7'
			}
		}

        
    }
}
