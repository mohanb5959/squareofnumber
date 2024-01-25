pipeline {
  agent any
  parameters {
    string defaultValue: '10', description: 'Enter a value', name: 'One'
  }
  stages {
    stage('Square of a number') {
      steps {
        script {
          def One = params.One as int
          res = One*One
          echo "Result is ${res}"
        }
      }
    }
  }
}
