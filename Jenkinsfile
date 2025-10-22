
pipeline{
			agent {
					label {
							label "Slave-1"
							customWorkspace "/mnt/myWorkspace"
					
					}
			
			}
			
			stages{
					stage("Stage-1"){
							steps{
									echo "This is stage-1"							
							}	
						
					}
					stage("Stage-2"){
						steps{
									echo "This is stage-2"
						
						}			
					
					}
					
					stage("Stage-3"){
						steps{
									sh "mkdir newFolder"
									echo "newFolder has been created!"
						
						}			
					
					}
			
			
			
			}
			
			
			



}
