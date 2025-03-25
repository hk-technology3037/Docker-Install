# Docker-Install
Docker install in kali linux


1:- install kali linux and use this comands
  - []  1: sudo apt-get install xrdp
 - []  2: sudo systemctl enable xrdp
 - []  3: sudo systemctl start xrdp
 - []  4: sudo apt-get install leafpad 
 
2:- Use this comands to install Docker in kalilinux
 
  [] 1: sudo apt update
  [] 01: sudo apt upgrade
  [] 2: sudo apt install docker.io
  [] 3: sudo systemctl enable docker --now
  [] 4: sudo usermod -aG docker $USER
  [] 5: echo "deb [arch=amd64 signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/debian bookworm stable" | \
        sudo tee /etc/apt/sources.list.d/docker.list
  [] 6: curl -fsSL https://download.docker.com/linux/debian/gpg |
        sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
  [] 7: sudo apt update
  [] 8: sudo apt install -y docker-ce docker-ce-cli containerd.io
  [] 9: sudo apt install docker-compose
