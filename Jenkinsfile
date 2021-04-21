pipeline{
    agent {label 'UBUNTU'}
    trigger {pollscm('* * * * *')}
    stages{
        stage{
            steps{
                git branch:'declartive' url:'https://github.com/karthik2111/game-of-life.git'
                sh 'mvn compile'
            }
        }
    }
}

