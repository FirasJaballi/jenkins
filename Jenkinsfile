pipeline {

 agent any

 tools {jdk "JDK_17", maven "MVN_3.8.7"}

 stages {

 stage('GIT') {

           steps {

               git branch: 'master',

               url: ' https://github.com/hwafa/timesheetproject.git'

          }

     }

 stage ('Compile Stage') {

 steps {

 sh 'mvn clean compile'

 }

 }

 }

}
