pipeline
{
    agent any
        stages
        {
            stage('clone')
            {
                steps
                {
                    git branch:'csea',url:'https://github.com/shyamkumar7871/week1-demo.git'
                }
            }
            stage('build')
            {
                steps
                {
                    sh 'javac Vbit.java'
                }
            }
            stage('run')
            {
                steps
                {
                    sh 'java Vbit'
                }
            }
        }
    }
