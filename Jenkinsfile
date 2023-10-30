//node {
//    stage 'Create build output'
    
    // Make the output directory.
//    sh 'touch /tmp/DEVjenkinstest.bks'
//}


node {

    stage('CREATE') {
        sh 'ls -l /tmp/testforjenkins'
        sh ' echo files listed'
      }
    
    stage('EDIT') {
        sh 'rm -rf $(find /tmp/testforjenkins -type f -mtime +2)'
        //sh 'find /tmp/testforjenkins -type f -mtime +2 -exec rm -rf {} \\;'
        sh 'echo files older than 2 days deleted'
        }

    stage('INSERT') {
        sh 'echo files older than 2 days deleted'
        }

    }

