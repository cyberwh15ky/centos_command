How to Linux service status:
!!! FYI
[+]: running
[-]: not running
[?]: status option not implemented

- service --status-all
![image](https://github.com/cyberwh15ky/centos_command/assets/142871997/9e7613e3-5564-4541-b473-1e2f79ec4e0c)
- sudo service --status-all | grep "service name"
![image](https://github.com/cyberwh15ky/centos_command/assets/142871997/55485252-dfa9-4f6e-8129-7d4a6b2e6f3c)
- sudo service "service name" status
![image](https://github.com/cyberwh15ky/centos_command/assets/142871997/0cc7c913-2909-4f99-9ae9-e518676ada0f)


How to install or check SSH：
View status:
- sudo systemctl status ssh
![image](https://github.com/cyberwh15ky/centos_command/assets/142871997/6a358593-3412-4e08-bfbb-211596e9f713)
![image](https://github.com/cyberwh15ky/centos_command/assets/142871997/e67bf821-677e-4eec-9b3b-aa9c3e35c4f0)


Installing ssh in Ubuntu for server：
- sudo apt install openssh-server
- sudo systemctl enable ssh
- sudo ufw allow ssh  
![image](https://github.com/cyberwh15ky/centos_command/assets/142871997/2d6ce420-b8aa-4aeb-beeb-dd1a6c50532d)  
![image](https://github.com/cyberwh15ky/centos_command/assets/142871997/a1a088f3-b226-4cab-9235-6adc7b4c5453)


Installing ssh in Ubuntu for client：
- sudo apt-get update
- sudo apt-get upgrade
- sudo apt-get install openssh-client


IF show "WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!" Go to the file delete all data or change the file location.
![image](https://github.com/cyberwh15ky/centos_command/assets/142871997/1a4cff27-f95e-4408-bb65-7e68fbfb86dc)

