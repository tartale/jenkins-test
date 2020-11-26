node {
  properties(
    [
      parameters(
        [
          string(
            name: 'YOURNAME', 
            defaultValue: 'world', 
            description: 'Name to greet'
          )
        ]
      )
    ]
  )

  timestamps {

      stage('Say Hello') {
          echo "Hello ${params.YOURNAME}.  Everything is awesome!"
       }
  }
}
