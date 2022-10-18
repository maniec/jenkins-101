# jenkins-101

Trying Pipeline configurations, plugins, etc

### Agent
- The agent directive, which is required, instructs Jenkins to allocate an **_executor_** and _**workspace**_ for the Pipeline 
- Without an agent directive, not only is the Declarative Pipeline not valid, it would not be capable of doing any work!
- By default, the agent directive ensures that the source repository is checked out and made available for steps in the subsequent stages

### Steps
- sh '...'
- echo "..."
- junit '...'
- 