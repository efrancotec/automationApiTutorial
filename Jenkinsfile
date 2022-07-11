pipeline{
	
	agent any
	
	stages{
	
		stage("Information"){
			steps{
				echo 'Search collection'
			}
		}
		stage("Run test cases"){
			steps{
				echo 'Testing the application'
        bat 'C:/Users/esfra/AppData/Roaming/npm/newman run C:/Users/esfra/Desktop/postman-collection/AutomationPractice.postman_collection.json -e C:/Users/esfra/Desktop/postman-collection/Automation-v1.postman_environment.json'
			}
		}
		stage("Finish"){
			steps{
				echo 'Test finish'
			}
		}
	}
}
