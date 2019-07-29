pipeline{agent any 
         stages{ stage('Clone Repo') 
          { steps 
                  { 
                   sh "scp file://index.html localhost:index.html",
                    sh "cd ~",
                    sh "cp /var/lib/jenkins/workspace/test-ssh1/index.html ~/index.html"}
           }
         }
        
        }
