# Docker Install
Docker install in kali linux: 
<a href="https://hktechnology.in"><img src="https://i.ibb.co/3pyMgxV/HK-Logo.png" width="25"></img></a>


# **1: install kali linux and use this comands For RDP access.**
<img src="https://yoolk.ninja/wp-content/uploads/2020/06/Apps-Ms-Remote-Desktop-1024x1024.png" width="50">

  -  sudo apt-get install xrdp -y
  -  sudo systemctl enable xrdp
  -  sudo systemctl start xrdp
 
# **2: Use this comands to install Docker in kali linux.**
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_%28container_engine%29_logo.svg/2560px-Docker_%28container_engine%29_logo.svg.png" width="100">

 - sudo apt-get update
 - sudo apt-get upgrade -y
 - sudo apt-get dist-upgrade -y
 - sudo apt install docker.io -y
 - sudo systemctl enable docker --now
 - sudo usermod -aG docker $USER
 - echo "deb [arch=amd64 signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/debian bookworm stable" | \ sudo tee /etc/apt/sources.list.d/docker.list
 - curl -fsSL https://download.docker.com/linux/debian/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
 - sudo apt update
 - sudo apt install -y docker-ce docker-ce-cli containerd.io
 - sudo apt install docker-compose



# **3: Install CASAOS IF Require.**
<img src="https://wiki.casaos.io/_assets/casaos-no-text.svg" width="50">

 - curl -fsSL https://get.casaos.io | sudo bash

