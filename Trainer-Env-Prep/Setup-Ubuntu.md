# Trainer Tasks

## Setup Shell in a Box (Access Ubuntu SSH/Shell/Console from Browser)
 - Refer: https://github.com/shellinabox/shellinabox
 - Refer: https://linoxide.com/web-remote-your-server/
```
sudo apt -y update
```

```
sudo apt -y install openssl
```

## Install Docker
```
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh
sudo usermod -aG docker $USER
exit
```

## Setup multiple users in Ubuntu
- For each participant, we need to setup login accounts
```
sudo groupadd docker
for ((i=1;i<=200;i++)); do
	export username="u$i"
	sudo useradd -m -p "p2" $username;sudo usermod -aG sudo $username;sudo usermod -aG docker $username;echo $username:p | sudo /usr/sbin/chpasswd;sudo chown -R  $username:root /home/$username
done
```

- Comman softwares
```
sudo apt -y update
sudo apt -y install tree
```

-  Clone Git Repo
```
cd
git clone
cd
```

- Customize linux prompt
```
cat ~/.bashrc
echo 'export PS1="\e[0;31m\e[50m\u@\h\n\w \e[m\n$ "'   >> ~/.bashrc
cat ~/.bashrc
exit
```

- Setup guacamole
  - Refer: https://github.com/boschkundendienst/guacamole-docker-compose
```
git clone "https://github.com/atingupta2005/guacamole-docker-compose"
cd guacamole-docker-compose
./prepare.sh
docker compose up -d
curl https://localhost:8443
```
- Note: Need to use - https
- Credentials: guacadmin / guacadmin

### Setup Python
```
sudo apt install software-properties-common -y
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.10
python3.10 --version
sudo apt-get install -y python3-pip
sudo apt-get install -y python3-venv
mkdir python_venv
cd python_venv/
python3 -m venv .
source  bin/activate
python -V
```

### Setup Jupyter Lab
```
sudo apt install python3-dev git curl
curl -L https://tljh.jupyter.org/bootstrap.py | sudo -E python3 - --admin $USER
curl https://rgvmpyspark.eastus.cloudapp.azure.com/
```

- Setup R Studio
```
sudo apt -y update
sudo apt-get -y install r-base
sudo apt-get  -y install gdebi-core
wget https://download2.rstudio.org/server/bionic/amd64/rstudio-server-2021.09.0-351-amd64.deb
sudo gdebi rstudio-server-2021.09.0-351-amd64.deb
free -h
curl http://localhost:8787
```
