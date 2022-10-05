pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
       }
        stage('Run') {
            steps {
                echo 'Running the compiled java code.'            }
                sh 'java Hello'       
            }
       }
}
