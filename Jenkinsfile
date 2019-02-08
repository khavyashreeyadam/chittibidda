node {
        stage('config')
        {
    dir ('chitti') {
        writeFile file:'dummy', text:''
                }
         }
        stage('create'){
             dir ('chitti') {
             writeFile file:'chittitalli', text:''
        }        
        }
        stage('content'){
                sh 'echo {hia hai} >> chittitalli.txt'
        
        }
}
