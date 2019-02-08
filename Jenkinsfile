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
               def file1 = new File('chitti.txt')
file1.write 'Working with files the Groovy way is easy.\n'
        
        }
}
