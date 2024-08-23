pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh 'mvn -DskipTests clean package'
            }
        }
         stage("Test"){
            steps{
                sh 'mvn test'
            }
        }
    }
}
