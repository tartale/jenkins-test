pipeline {
   agent any
   options {
       timestamps()
       disableConcurrentBuilds()
       timeout(time: 2, unit: 'HOURS')
   }

   parameters {
     string(
       name: 'STATEMENT', 
       defaultValue: 'Everything is awesome!',
       description: 'Something to say'
     )
   }
   
   stages {
      stage('Say Hello') {
         steps {
            echo "Hello ${env.YOUR_NAME}.  ${params.STATEMENT}"
         }
       }
   }
}
