node {
        stage('build'){
                echo  'hai hema'
        }
        stage('make file'){
             writeFile file: 'groovy1.txt', text: 'Working with files the Groovy way is easy.'
           sh 'ls -l groovy1.txt'
           sh 'cat groovy1.txt'
        }
        stage('makedir'){
                sh 'mkdir thisis'
        }
}
      
