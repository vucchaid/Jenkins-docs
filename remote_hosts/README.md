# Setting up remote hosts for Jenkins

If we want to run some scripts or commands in another system/host for various reasons such as running tasks parellely such as pinging a service to check if service is up or to run scripts parallely, then we use remote hosts to do it.

<br/>

Jenkins will SSH into the configured remote_host and will run the job in that host.

<br/>

In this excerise, we will use docker itself to create a container, which will act as another system/host for us. In reality, there will be another system setup to be used as remote host, however, steps will remain same. 

<br/>

Follow steps present in [instructions](https://github.com/vucchaid/Jenkins-docs/blob/main/remote_hosts/remote_hosts.txt) file.