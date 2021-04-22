node(){
    stage('scm'){
        git 'https://github.com/karthik2111/game-of-life.git'
    }
    stage('build'){
        sh 'mvn package'
    }
}