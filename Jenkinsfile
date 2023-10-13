pipeline{
    agent any
    stages{
        stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/berilkoko97/demo-counter-app'
            }
        }

        stage('Unit Testing'){
            steps{
                sh 'mvn test'
                
    }


}