
pipeline{
    agent any

    stages{

stage('parallelpipe')
{
    parallel{

        stage('one'){
        agent {label 'label1'}
        steps {
        echo 'Hello Label One'
        }
        }
stage('two'){
        agent {label 'label2'}
        steps {
        echo 'Hello Label 2'
        }
        }


}


    }
}
}
