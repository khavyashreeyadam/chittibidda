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
        stage('addcontent'){
        def readContent = readFile "chittitalli"
writeFile file: "sample", text: "$readContent Version=$projectVersion\n"
echo "${chittitalli.txt}"
        }
}
