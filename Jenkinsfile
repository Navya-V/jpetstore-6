pipeline {
    agent any
    environment {
        MAVEN_HOME = tool ('maven')
    }
      stages {
          stage ("git") {
              steps {
                  script {
                      git ( url :"https://github.com/Navya-V/jpetstore-6.git" ,
                            branch : "master" ,
                            credentialsId : "")
                  }
              }
          }
}