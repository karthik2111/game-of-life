node(){
    stage('scm'){
        git branch master url:'https://github.com/karthik2111/game-of-life.git'
    }
    stage('build'){
        sh 'mvn package'
    }
}