<h2> This is the project where i setup microsoft  server and exchange server </h2>
<h4> created the VM named server2019KK-DC01 in Hyper-v in windows 10 Education and installed the Operating system of window server 2019 <h4>
<img src= "images\Picture1.jpg" >
<h3>start the server and login with the password as administrator <h3>
<img src="images\Picture2.jpg" >
<h3> put  the following static IPv4 in the VM </h3>
<h4 >IP Address: 192.168.1.10 <br>
Subnet Mask: 255.255.255.0  <br>
DNS Server: 192.168.1.10 <br> <h4>
<img src= "images\Picture3.jpg"  >
<h4> Enable remote desktop in the vm <h4>
<img src= "images\Picture4.png" >
<h4> install role and features <h4>
<img src = "images\Picture5.jpg" >
<h4> Active diretory domain services 
 and dns services <h4>
<img src="images\Picture6.jpg" >
<img src="images\Picture7.jpg" >
<img src="images\Picture8.jpg">
<h3> Add a new forest as domainKK.com </h3>
<img src="images\Picture9.jpg">
<h4> created two users in active directory <h4>
<h5> created another machine in Hyper-v for MSExchange ,start the server and put the following ipv4 in this ,<br>IP Address: 192.168.1.5 <br>
Subnet Mask: 255.255.255.0<br>
DNS Server: 192.168.1.10<br>
</h5>
<img src="images\Picture10.jpg">
<h5> add this to the active directory <h5>
<img src="images\Picture11.jpg">
<img src="images\Picture12.jpg">
install different features to it using powershell scripts,mount the msexchange and access it
<img src="images\Picture13.jpg">
<img src="images\Picture14.jpg">
<img src="images\Picture15.png">
<h5>logged in with the domainkk/KK2019exadmin and password </h5> 
<img src="images\Picture16.png">
<h4> opened the link http://MSExchange2019K.domainKK.com for the outlook and this page appear </h4>
<img src="images\Picture17.png">
<img src="images\Picture18.png">
<img src="images\Picture19.png">

