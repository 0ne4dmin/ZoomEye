# ZoomEye
A script used to get data from ZoomEye, a special search engine to search devices connected to network(https://www.zoomeye.org/)
just like Shodan(https://www.shodan.io/)

## getZoomEyeIpList.py
This script gets 'ip and port'(default) that you search from ZoomEye, which needs to provide a access_token. So, the first time 
you run this script, your need to provide your account and password registered to ZoomEye to create such a access_token.

Then, input your query(weblogic in this sample), and start page(1) till end page(3). You will get about 30 items save to file.
</br>

### Sample
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++</br>
[-] info : access_token file is not exist, please login </br>
[-] input : username :[your email account]</br>
[-] input : password :[your password]</br>
[\*] please input search string : weblogic</br>
[\*] please input start page : 1</br>
[\*] please input number of pages you want to retrieve : 3</br>
https://api.zoomeye.org/host/search?query=weblogic&page=1</br>
115.112.99.254 8010</br>
115.85.207.196 8008</br>
110.249.133.214 79</br>
115.233.221.139 8007</br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++</br>
</br>


### About This Script
author  : evilclay </br>
http://www.cnblogs.com/anka9080/p/ZoomEyeAPI.html</br>
------- Modified by -------</br>
starnight_cyber@foxmail.com</br>
Time : 2016.12.8/2017.7.17</br>
</br>
