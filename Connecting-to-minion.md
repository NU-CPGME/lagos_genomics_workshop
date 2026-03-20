# Connecting to MinION via WiFi

1. In the settings sidebar, click the networks settings icon. It looks like a gear and is underneath the question mark icon
2. Activate the WiFi and connect to your router with the WiFi router's username and password
3. Record the **IP address**. This may be different every time you activate WiFi on the nanopore
4. On your computer that is connected to the same WiFi router, open [FileZilla](https://filezilla-project.org/)
5. In the top bar, enter the following information and press "Quickconnect"
    * Host: **IP address** that you recorded above
    * Username: minit
    * Password: minit 
    * Port: 22 (or leave blank)

6. In the Remote window on the right, navigate to `/data`
7. Find your run and drag it into an appropriate folder on Local site side (left window)