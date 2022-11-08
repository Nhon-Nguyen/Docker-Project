# Update System
<img width="496" alt="update" src="https://user-images.githubusercontent.com/114501322/200607127-bf2e276e-8dc8-44bb-ad91-c5b8e2e4b897.png">

# Install Docker and Test with 'hello-world'
The commands traight from class document:
- sudo apt update
- sudo apt install ca-certificates curl gnupg lsb-releasecurl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
- echo "deb [arch=$(dpkg --print-architecture)signed-by=/usr/share/keyrings/docker-archive-keyring.gpg]https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee/etc/apt/sources.list.d/docker.list > /dev/null
- sudo apt update
- sudo apt install docker-ce docker-ce-cli containerd.io
- sudo usermod -aG docker sysadmin
- sudo docker run hello-world

<img width="497" alt="test docker" src="https://user-images.githubusercontent.com/114501322/200607319-9318bfd7-e132-4744-ba23-ea23320d63e7.png">
