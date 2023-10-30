//node {
//    stage 'Create build output'
    
    // Make the output directory.
//    sh 'touch /tmp/DEVjenkinstest.bks'
//}


node {

    stage('CREATE') {
        sh 'ls -l /tmp/test'
        sh ' echo files listed'
      }
    
    stage('EDIT') {
        sh 'mkdir /tmp/test/2023-001'
        sh 'cd /tmp/test/ && rf -rf $(find ./ -type d -name "2023-*" -mmin +3)'
        //sh 'find /tmp/testforjenkins -type f -mtime +2 -exec rm -rf {} \\;'
        sh 'echo files older than 2 days deleted'
        }

    stage('INSERT') {
        sh 'echo files older than 2 days deleted'
        }

    }

