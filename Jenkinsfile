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
            echo "Hello ${params.YOUR_NAME}.  Everything is awesome!"
         }
       }
   }
}
