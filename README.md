# umszki-docker
Nginx demo with Docker on Ubuntu 16.04.4 LTS Server

The script assumes you have an installed Ubuntu 16.04.4 LTS Server with an `ubuntu` user who can be privileged.

After you've run the script you can execute the following command:

```bash
docker build -t webserver-image .
docker run -d -p 80:80 webserver-image
```
