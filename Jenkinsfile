pipeline { 
    agent any  
    stages { 
        stage('sample1') {
          steps {
            echo 'summition'
          }
        }
        stage('sample 2') { 
            steps { 
               echo 'addition...' 
               bat 'python main.py'
               //bat 'mvn package'
            }
        }
   }
}
