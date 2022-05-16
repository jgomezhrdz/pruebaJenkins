pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                script {
                    echo "build docker image"
                    sh "docker build -t pruebaJenkins ."
                    echo "OK"
                }
            }

        }
        stage("Deploy"){

        }
    }
}