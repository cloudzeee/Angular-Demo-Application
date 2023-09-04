pipeline {

    agent any

 

    stages {

        stage('Checkout') {

            steps {


                checkout scm

            }

        }

 

        stage('Build') {

            steps {

                sh 'npm install -g @angular/cli'             

                sh 'npm install'

 

     

                sh 'ng build --prod' 

            }

        }

 

       

    }



}
