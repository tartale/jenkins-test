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
       description: 'Name to greet'
     )
   }

   stages {
      stage('Say Hello') {
         steps {
            echo "Hello ${params.YOUR_NAME}.  Everything is awesome!"
         }
       }
   }
}
