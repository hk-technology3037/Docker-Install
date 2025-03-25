# Docker-Install
Docker install in kali linux:


1:- install kali linux and use this comands For RDP access
  -  sudo apt-get install xrdp
  -  sudo systemctl enable xrdp
  -  sudo systemctl start xrdp

![Alt text](https://e7.pngegg.com/pngimages/39/564/png-clipart-docker-logo-landscape-tech-companies.png)
 
2:- Use this comands to install Docker in kali linux
 
 - sudo apt update
 - sudo apt upgrade
 - sudo apt install docker.io
 - sudo systemctl enable docker --now
 - sudo usermod -aG docker $USER
 - echo "deb [arch=amd64 signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/debian bookworm stable" | \ sudo tee /etc/apt/sources.list.d/docker.list
 - curl -fsSL https://download.docker.com/linux/debian/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
 - sudo apt update
 - sudo apt install -y docker-ce docker-ce-cli containerd.io
 - sudo apt install docker-compose

![Alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQxZxtKEJE_l7iE7kDVcpCIZamkaXKJXdNf8g&s)

3:- Install CASAOS IF Require
 - curl -fsSL https://get.casaos.io | sudo bash
