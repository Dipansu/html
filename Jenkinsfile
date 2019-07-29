pipeline{agent any 
         stages{ stage('Clone Repo') 
          { steps 
                  { 
                   sh "scp file://index.html localhost:index.html",
                    sh "cd /home/ec2-user",
                    sh "cp /var/lib/jenkins/workspace/test-ssh1/index.html /home/ec2-user/index.html"}
           }
         }
        
        }
