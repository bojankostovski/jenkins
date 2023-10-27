
//node {
//    stage "Create build output"
    
    // Make the output directory.
//    sh "touch /tmp/DEVjenkinstest.bks"
//}


node {

    stage('CREATE') {
        sh "touch /tmp/DEVjenkinstest.bks"
        sh "touch /tmp/DEVjenkinstest2.bks"
        sh " echo files created"
      }
    
    stage('EDIT') {
        sh "chmod 777 /tmp/DDEVjenkinstest2.bks"
        sh "echo changed permissions"
        }

    stage('INSERT') {
        sh "echo test>>/tmp/DEVjenkinstest2.bks"
        sh "echo written in file"
        }
      }