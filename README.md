# docker-jenkins-master
Jenkins Master

## Service availables:

- **docker-compose.yml**

    Use this configuration for starting the Jenkins server. 
    Remember to set the required variables first!

    Required variables:

    - **JENKINS_HOME**
    - **JENKINS_HTTP_PORT**
    - **JENKINS_REMOTE_API_PORT**

    ### Start with:

        $ docker-compose up -d
  
- **docker-compose-backup.yml**

    Use this configuration to backup the jenkins home folder.
    Remember to set the required variables first!

    Required variables:

    - **JENKINS_HOME**
    - **JENKINS_BACKUP_HOME**

    ### Start with:

        $ docker-compose -f docker-compose-backup.yml up
