#Where is Robots :
soltion:</br>
you need to add this ' robots.txt ' in url </br>
ex : 172.206.91.8/robots.txt</br>
sorry i don't have access now in platform to take picture</br>

# Headers
Soltion: 
you need to add this HTTP header in request</br>
1- User-Agent: TTU_BROWSER</br>
This HTTP header use for identify your browser</br>
2- Referer: ttu.edu.jo</br>
use for identify from where you come</br>
3-Cookie:Role=admin</br>
Some of its uses in the past were used for identification and are now used to identify you when you visit the site again</br>

![image](https://github.com/SlmanAlsayyed/writeup/assets/100826854/4b819c82-a9b4-4a81-843e-c5e82151b061)

#SQL 1
basic SQL Injection, just put any basic payload in search bar</br>
---Payload = your malicios query in this case</br>

![image](https://github.com/SlmanAlsayyed/writeup/assets/100826854/37cb1c7a-6df6-4b52-a9db-d969f99c6ac3)

#SQL 2
this challenge based on Blind sql injection </br>
you need to fetch the flag character by character  , the list of letter in source code is very useful  </br>

this is payload<br>
'UNION SELECT information FROM info WHERE SUBSTRING((SELECT information FROM info WHERE information LIKE 'T%'),1,1)='T'-- -</br>

search for  'Blind SQLi' to understand how exploit it






