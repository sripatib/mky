pipeline{

    agent any
    stages{
        stage ('stage 1'){
            when{expression{env.VALUE == 'y'}}
           steps{
               echo "this is stage 1"
           }
        }

        stage ('stage 2'){
           steps{
               echo "this is stage 2"
           }
        }
    }
}
