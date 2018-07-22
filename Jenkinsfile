node {
  stage("Checkout")
  {
     sh 'echo "checkout stage"'
     //sh 'git submodule update --init'
  }

  stage("Build")
  {
     sh 'echo "build stage"'
     sh 'java --version'
  }

  stage("Static Analysis")
  {
      sh 'echo "running static analysis stage"'
  }

  stage("Unit Test")
  {
     sh 'echo "running test stage"'
  }

  stage("Release Lib")
  {
      sh 'echo "running release stage"'
  }
}
