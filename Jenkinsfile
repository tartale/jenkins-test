pipeline {
   agent any
   options {
       timestamps()
       disableConcurrentBuilds()
       timeout(time: 2, unit: 'HOURS')
   }

   parameters {
     string(
       name: 'YOUR_NAME', 
       defaultValue: 'world',
       description: 'Someone'
     )
     string(
       name: 'STATEMENT', 
       defaultValue: 'Everything is really awesome!',
       description: 'Something to say'
     )
   }
   
   stages {
      stage('Say Hello') {
         steps {
            echo "Hello ${params.YOUR_NAME}.  ${params.STATEMENT}"
         }
       }
   }
}
