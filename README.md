## Configure required hosts
```bash
#######################################
# Windows example

## Edit hosts file
C:\Windows\System32\drivers\etc\hosts

## include registers bellow
127.0.0.1 datestarxxx.com

#######################################
# Linux example

## Edit resolv.conf file
vim /etc/resolv.conf

## include registers bellow
127.0.0.1 datestarxxx.com
```

## Up project
```shell
docker-compose up
```

## Response to user
```text
You'll need a few things to test this out.

Download the repository from GitHub.
Configure the host as indicated in the README file.
With Docker installed, navigate to the project folder.
Place your project inside the 'app' folder or adjust it to the desired path.
Start the system with 'docker-compose up'.
Give it a try!
```

## Conclusion
```text
The work was successfully completed, the file refactoring was finished and delivered to the client.
However, they didn't understand that the action solved the issue.
I believe the client didn't want to validate if the configuration resolved the problem before deploying it to production.
```
