pipeline {
    agent any

    stages {
        stage ('Installation') {

            steps {
                    
            }
        }


        stage ('Build Stage') {

                    steps {

                          

                    }
                }


        stage ('Deploy Stage') {

                    steps {
                       sh 'sudo scp -i /home/dc-admin/digpemkey.pem -r C:\Windows\System32\config\systemprofile\AppData\Local\Jenkins\.jenkins\workspace\Mohan-Tech/* dc-admin@10.100.1.61:/usr/share/nginx/html'
                    }
        }
    }
}
