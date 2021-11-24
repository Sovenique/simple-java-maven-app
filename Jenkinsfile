pipeline {
     agent {
        docker { image 'eddevopsd2/maven-java-npm-docker:mvn3.8.3-jdk17-npm6.14.4-docker' }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean install' 
            }
        }
    }
}
