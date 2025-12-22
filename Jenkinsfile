pipeline{
    agent any

    stages{
        stage('checkout'){
            steps{
                git 'https://github.com/A-suma/java-hello-world-with-maven.git'
            }
        }
        stage('test'){
            steps{
               sh 'mvn test'
            }
        }
        stage('build'){
            steps{
                sh 'mvn package'
    }
}
