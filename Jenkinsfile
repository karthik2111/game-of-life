node(){
    stage('scm'){
        git clone 'https://github.com/karthik2111/game-of-life.git'
    }
    stage('build'){
        sh 'mvn package'
    }
}