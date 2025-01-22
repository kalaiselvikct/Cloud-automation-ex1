# Cloud-automation-ex1
Webpage_login
Steps to host a webapplication through github code. 
1.	In google, search for “codepen”. Open the first link ->click searchpens->search for “login”.
2.	 Click a page that is with only “html”and  “Css”. Copy the html code 
3.	Paste it in “VScode” – new file and save it as “index.html”. add the following 3 lines as first lines in index.html file
<head>
<link=”css style sheet” href = “./style.css”>
</head>
Save the file as index.html

4.	The same way copy the sytlesheet code from codepen and paste it in a new file called style.css in vscode.
5.	Press control + tilde in vscode, a cmd prompt will open ( below the same editor)
6.	On left pane -> extentions -> click live server and click install 
7.	Open the files index.html from desktop folder
8.	In right bottom corner click “Golive”.
9.	A form will open.

Git hub 

10.	Push the index.html and style.css in a new repository in github. You can use this link for these files.
https://github.com/kalaiselvikct/Cloud-automation-ex1

11.	In AWS management console, Create a linux instance with SSH, HTTP,HTTPs security group and create a  secutity key rsa, pem key
Launch the instance
Connect with the instance
Execute the following commands
$ sudo su
yum install httpd -y
yum install git -y
git –version
cd /tmp
git clone “url path of html file from github”
ls
cd dirctory name
mv ./index.html  /var/www.html/
ls
mv ./style.css  /var/www/html/
ls
ls  /var/www/html
systemctl start httpd
systemctl enable httpd
12.	go to browser , paste the EC2 instacne public ip to access the app

