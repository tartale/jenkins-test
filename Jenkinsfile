parameters {
  string(
    name: 'YOURNAME', 
    defaultValue: 'world', 
    description: 'Name to greet'
  )
}

timestamps {
  stages {

    stage('Say Hello') {
        steps {
          echo "Hello ${env.YOURNAME}.  Everything is awesome!"
        }
     }
  }
}
