pipeline {

    
        agent {
		
		       label {
			          
					  label 'built-in'
			   }
			   
			   }
			   
			   stages  {
			   
               stage ('one') {

                       steps {


                              echo 'hello master'
                              sleep 10
                                        }
										

                        }
						
				stage ('two') {
				
				        
						 steps {
						        echo 'hello velocity'
								
								sleep 5

							sh 'rm -rf *'
						 }
		

        }
		
	}
	
	
	}





