# ngrok
NGROK INSTALLATION 

````bash 
pkg up -y
pkg i curl -y
curl https://raw.githubusercontent.com/ShTasrif/ngrok/main/ngrok --output /data/data/com.termux/files/usr/bin/ngrok
chmod +x /data/data/com.termux/files/usr/bin/ngrok
````
#### Adding auth token

<p>Create an account on <a href="https://ngrok.com/">ngrok</a></p>

<p>Generate your auth token.</p>

#### Now open your termux and type : `ngrok authtoken <ngrok_token>` for add your authtoken.


Now type `ngrok http 80` for test.

### <p align="center"><img src="https://raw.githubusercontent.com/ITSN0B1T4/itsn0b1t4/main/img/ngrok.png"></p>

