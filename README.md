# Deploy-Docker-Container-on-AWS
Learn how to Deploy Docker Container on AWS 

![image](https://user-images.githubusercontent.com/39345855/77860782-0c865f80-71df-11ea-822a-b544e4afaa47.png)




### Tutorial Video :  https://www.youtube.com/watch?v=awFLzy0XwXo


## New Steps
Ubuntu 21.04 (hirsute)
```
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu hirsute stable"
```
Ubuntu 20.10 (Groovy)
```
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu groovy stable"
```
Ubuntu 20.04 (Focal)

```
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

```
Ubuntu 19.10 (Eoan)

```
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu eoan stable"

```
Ubuntu 19.04 (Disco)

```
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu disco stable"

```
Ubuntu 18.10 (Cosmic)

```
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu cosmic test"

```
Ubuntu 18.04 (bionic)

```
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"

```
Ubuntu 17.10

```
docker-ce package is available on the official docker (Ubutu Artful) repository , to install it use the following commands :

sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu artful stable"

```
Ubuntu 16.04
You can install docker-ce on Ubuntu as follows:

```

sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu xenial stable"

```
Run the following:


```
sudo apt update
apt-cache search docker-ce

```
sample output:

docker-ce - Docker: the open-source application container engine
Install docker-ce:

For Ubuntu 16.04 you need to run sudo apt update. For Ubuntu 18.04 and higher, add-apt-repository will execute apt update automatically:


```
sudo apt install docker-ce

```
To check the available and permitted Ubuntu codenames:


```
curl -sSL  https://download.docker.com/linux/ubuntu/dists/ |awk -F'"' 'FNR >7 {print $2}'
sample output (Results may be different after the directory updates):

../
artful/
bionic/
cosmic/
disco/
eoan/
focal/
groovy/
hirsute/
trusty/
xenial/
yakkety/
zesty/
Docker , OS requirements

```

## Commands on Ubuntu Server  

```bash
sudo apt-get update
```

```bash
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
```

```bash
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io
```



```bash
apt-cache madison docker-ce
```


```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io
```


```bash
sudo apt install docker.io
```


```bash
sudo apt install docker-compose
```

##
