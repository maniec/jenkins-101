# jenkins-101

Trying Pipeline configurations, plugins, etc

### Java
https://youtu.be/qx3XK82BZPk

### Maven
https://youtu.be/V-VFrYF_Z1Y

### Agent
https://www.jenkins.io/doc/book/security/controller-isolation/
https://youtu.be/99DddJiH7lM
- The agent directive, which is required, instructs Jenkins to allocate an **_executor_** and _**workspace**_ for the Pipeline 
- Without an agent directive, not only is the Declarative Pipeline not valid, it would not be capable of doing any work!
- By default, the agent directive ensures that the source repository is checked out and made available for steps in the subsequent stages

### Steps
- sh '...'
- echo "..."
- junit '...'

### Credentials
- Declarative Pipeline syntax has the **_credentials()_** helper method (used within the **_environment_** directive)
- It supports **_secret text_**, **_username and password_**, as well as **_secret file_** credentials