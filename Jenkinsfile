pipeline {
    agent any


    stages {
        stage('SCM Checkout'){
            steps{  
              git 'https://github.com/apraka/downstream'
             }
        }  
        stage ('Compile Stage') {
          steps {
                echo 'Compile stage'
                }
            }
        stage ('Testing Stage') {
          steps {
                echo 'testing'
            }
       }     
}
}
