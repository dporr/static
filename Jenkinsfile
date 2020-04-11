pipeline{
    agent any
    stages{
        stage('Upload to AWS'){
            steps{
                retry(3){
                    withAWS(region:'us-east-2', credentials:'aws-static'){
                    s3Upload(file:'index.html', bucket:'project3-bucket-dporras', path:'')
            }
        }
    }

}