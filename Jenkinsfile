pipeline {
   agent any
   options {
       timestamps()
       disableConcurrentBuilds()
       timeout(time: 2, unit: 'HOURS')
   }

   stages {
      stage('Say Hello') {
         steps {
            echo "Hello ${env.YOUR_NAME}.  Everything is awesome!"
         }
       }
   }
}
