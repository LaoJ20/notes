# git

#### 1.Failed to connect to github.com port 443:Timed out  
第一步：打开ipaddress.com,查询如下两个域名，并分别记录下其对应的ip：  
1、github.com  
2、github.global.ssl.fastly.net  

第二步：更新host文件，C:\Windows\System32\drivers\etc  
192.30.253.112 github.com
151.101.185.194 github.global.ssl.fastly.net

第三步：dos窗口，清理下DNS  
ipconfig /flushdns

*********************************************************************

#### 2.



