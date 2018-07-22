node {
  stage("Checkout")
  {
     sh 'checkout stage'
     scm_vars = checkout scm

     //sh 'git submodule update --init'
  }

  stage("Build")
  {
     sh 'build stage'
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
