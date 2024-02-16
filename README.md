# azure_vm
Create an Azure VM, install node.js and git on it, and use SSH to clone the project with 'git clone'.

1. sudo apt update
2. sudo apt install nodejs
3. sudo apt install npm
4. sudo apt install git
5. git config --global user.name "Your Name"
6. git config --global user.email "your.email@example.com"
7. ls -al ~/.ssh
8. ssh-keygen -t rsa -b 4096 -C "your.email@example.com"
9. eval "$(ssh-agent -s)"
10. ssh-add ~/.ssh/id_rsa
11. cat ~/.ssh/id_rsa.pub
12. 於github中新增ssh key
13. ssh -T git@github.com
14. git clone git@gitlab.com:username/project.git
15. curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
16. source ~/.bashrc
17. nvm install 18.12.1
18. nvm alias default 18.12.1
19. npm install
20. npm install cors
21. scp -i inxSignage_key_0215.pem -r ./public/Media/video.mpd ./publia/video.mpd ./public/Media/video-242_dashinit.mp4 ./public/Media/video-360_dashinit.mp4 ./public/Media/video-audio_dashinit.mp4 azureuser@20.2.71.217:/home/azureuser/InxSignageService/public/Media



