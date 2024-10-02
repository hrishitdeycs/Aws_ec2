# Aws_ec2
## Getiing started with aws
### 1.Create an account on aws
### 2.Sign in to your account 
### 3.Go to your dashboard
### 4.Click on launch instance
### 5.Enter your server name and select ubuntu 
### 6.Click on create new key pair
### 7.Enter your key pair name then select .ppk and click on create new key pair
### 8.In the network settings click on allow http traffic from the internet
### 9.Click on launch instance
### 10.Copy the public ipv4 address from your instance and download putty. 
### 11.Paste the ip address in host name   
### 12.Click on SSH then auth then credentials
### 13.Click browse and open the key pair you downloaded
### 14.Click accept then type ubuntu and then press enter 
### 15.Use the commands
```bash
sudo apt update
```
```bash
sudo apt install apache2 -y
```
### 16.Use the commands 
```bash
cd /var/www/html
```
```bash
sudo rm index.html
```
```bash
sudo vi index.html
```
### 17.Edit the file and press Ctrl+C then type :wq
### 18.On the instance dashboard click on terminate running instance  

