# Install Docker-CE (Community Edition) in Debian Linux

Login as root or sudo
```
  # apt-get update

  # apt-get install apt-transport-https ca-certificates curl gnupg2 software-properties-common

  # curl -fsSL https://download.docker.com/linux/$(. /etc/os-release; echo "$ID")/gpg | sudo apt-key add -

  # apt-key fingerprint 0EBFCD88

  # sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/$(. /etc/os-release; echo "$ID") $(lsb_release -cs) stable"

  # apt-get update

  # apt-get install docker-ce

  # sudo curl -L https://github.com/docker/compose/releases/download/1.16.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose

  # chmod +x /usr/local/bin/docker-compose

  # docker-compose --version
```
