
//node {
//    stage "Create build output"
    
    // Make the output directory.
//    sh "touch /tmp/DEVjenkinstest.bks"
//}


node {

    stage('CREATE') {
      steps {
        sh "touch /tmp/DEVjenkinstest.bks"
        sh "touch /tmp/DEVjenkinstest2.bks"
        sh " echo files created"
      }
    }
    
    stage('EDIT') {
      steps {
        sh "chmod 777 /tmp/DEVjenkins2.bks"
        sh "echo changed permissions"
        }
      }


    stage('INSERT') {
      steps {
        sh "echo test>>/tmp/DEVjenkins2.bks"
        sh "echo written in file"
        }
      }
    }