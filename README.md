# Docker-Install
Docker install in kali linux


1:- install kali linux and use this comands
  -  sudo apt-get install xrdp
  -  sudo systemctl enable xrdp
  -  sudo systemctl start xrdp
  -  sudo apt-get install leafpad 
 
2:- Use this comands to install Docker in kalilinux
 
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


3:- Install CASAOS IF Nidded
 - curl -fsSL https://get.casaos.io | sudo bash
