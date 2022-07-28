# Jenkins Set Up
___
## installation
> install java
```
sud0 apt install openjdk-17-jre
```
```
java --version
```
> install jenkins

```
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
```


```
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
```

```
sudo apt-get update
```

```
sudo apt-get install jenkins
```
> Status
```
sudo service jenkins status
```
> paste it in the search bar of the browser
```
_ip_addres:8080
```
> yoyr password is in:
```
sudo nano /var/lib/jenkins/secrets/initialAdminPassword
```
