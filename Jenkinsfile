node {
  parameters {
    string(
      name: 'YOURNAME', 
      defaultValue: params.YOURNAME ?:'world',
      description: 'Name to greet'
    )
  }
  properties(
    [
        parameters(
            [
              string(
                name: 'YOURNAME', 
                defaultValue: params.YOURNAME ?:'world',
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
