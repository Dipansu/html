pipeline{agent any 
         stages{ stage('Clone Repo') 
          { steps 
                  {  
                   sh "scp ../index.html ec2-user@ip-172-31-34-193:index.html",
                   sh "cp /var/lib/jenkins/workspace/test-ssh1/index.html /home/ec2-user/index.html"}
           }
         }
        
        }
