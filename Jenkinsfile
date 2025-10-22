
pipeline{
			agent {
				label "qa"
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
									sh "rm -rf newFolder"
									echo "newFolder has been created!"
						
						}			
					
					}
			
			
			
			}
			
			
			



}
