# Checking the health of an elastic beanstalk application

1. Connect the EB CLI with the environment by `eb use <application-name>`.
2. Check the health of the environment with the `eb health` to display information about the servers running your application.
3. If health is not "OK", use the `eb logs` command to display the logs. then you can inspect the failure.