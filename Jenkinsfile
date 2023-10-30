//node {
//    stage 'Create build output'
    
    // Make the output directory.
//    sh 'touch /tmp/DEVjenkinstest.bks'
//}


node {

    stage('CREATE') {
        sh 'touch /tmp/allallow/DEVjenkinstest.bks'
        sh 'touch /tmp/allallow/DEVjenkinstest2.bks'
        sh 'touch /tmp/allallow/DEVjenkinstest3.txt'
        sh ' echo files created'
      }
    
    stage('EDIT') {
        sh 'chmod 777 /tmp/allallow/DEVjenkinstest2.bks'
        sh 'chmod 777 /tmp/allallow/DEVjenkinstest3.txt'
        sh 'echo changed permissions'
        }

    stage('INSERT') {
        sh 'echo test2>>/tmp/allallow/DEVjenkinstest2.bks'
        sh 'echo test2>>/tmp/allallow/DEVjenkinstest3.txt'
        sh 'echo written in file'
        sh 'find /tmp/allallow -type f -name "*.bks" -exec rm -rf {} \\;'
        }

    }

