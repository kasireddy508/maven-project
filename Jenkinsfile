success{
        emailext body: 'Project: ${JOB_NAME}   Build Number: ${BUILD_NUMBER}  Check console output at: ${BUILD_URL} successful',
        subject: 'Successful Build Details', 
        to: 'kasi@experienceflow.com'
        }
failure{
        emailext body: 'Project: ${JOB_NAME} <br>Build Number: ${BUILD_NUMBER}   Check console output at URL: ${BUILD_URL} failed',
        subject: 'Build Failure Details', 
        to: 'kasi@experienceflow.com'
        }       
