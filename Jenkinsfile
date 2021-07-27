node(
 docker {
        image 'maven:3.8.1-adoptopenjdk-11'
        label 'maven3.8'
        args  '-v /tmp:/tmp'
    }
){
  stage("clone"){
   git '' 
  }
}
