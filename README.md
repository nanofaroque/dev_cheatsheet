# dev_cheatsheet
### Run a service on EC2
* Create a service file hub.service
  
  `sudo vim /etc/systemd/system/email.service`
  
I have created one in this package already
  
* Now reload the service
`sudo systemctl daemon-reload`

* Start the service
`sudo systemctl start hub.service`

* Check the status of the service
`sudo systemctl status hub.service`

### 
Install gradle on ubuntu: https://linuxhint.com/installing_gradle_ubuntu/
