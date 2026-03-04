
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
				bat 'java-jar target/1.7'
			}
		}

        
    }
}
