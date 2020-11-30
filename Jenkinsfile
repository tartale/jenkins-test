pipeline {
   agent any
   options {
       timestamps()
       disableConcurrentBuilds()
       timeout(time: 2, unit: 'HOURS')
   }
   
   stages {
      stage('Say Wassup') {
         steps {
            echo "Hello ${env.YOUR_NAME}.  Everything is awesome!"
         }
       }
   }
}
