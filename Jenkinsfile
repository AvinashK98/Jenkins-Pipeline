pipeline{
		  agent none
		  
		  stages{
		  
					stage("Parallel-Execution"){
													
							parallel{
								      stage("Slave-1"){
											agent "Slave-1"
											steps{
													sh "mkdir slave-1"
													echo "The folder has been created"
											}
									  
									  }
									  stage("Slave-2"){
											agent "Slave-2"
											steps{
													sh "mkdir slave-2"
													echo "The folder has been created"
											}
									  
									  }
									
							
							
							}
					
					}
		  
		  
		  
		  }

}
