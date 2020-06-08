pipeline {
    agent any
 options {
        ansiColor('xterm')
    }
    stages {
        stage ('Master Compile Stage') {

            steps {
                    sh 'mvn clean compile'
            }
        }

        stage ('Master Testing Stage') {

            steps {
               
                    sh 'mvn test'
                
            }
        }


        stage ('Master Deployment Stage') {
            steps {
               
                    sh 'mvn deploy'
                
            }
        }
    }
}
