pipeline{
    agent any
    stages{
        stage('GIT'){
            steps{
                git url:'https://github.com/Naresh1770/game-of-life.git',
                    branch:'master'
            }
        }
        stage('MVN'){
            steps{
              sh 'mvn package'
            }
        }
    }
}