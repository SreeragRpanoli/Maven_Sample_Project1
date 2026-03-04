
pipeline{
    agent any
    
    stages{
        stage('Build'){
		steps{
			bat 'mvn install'
			}
		}
		stage('Run'){
			steps{
				bat 'java-jar target/1.5.jar'
			}
		}

        
    }
}
