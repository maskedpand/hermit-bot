#### HERMIT MD WHATSAPP BOT
Hermit-md - Simple whatsapp Multi Device whatsapp bot.

***

### SETUP
1. [![Fork me on GitHub](https://img.shields.io/github/forks/a-d-i-t-h-y-a-n/hermit-bot?style=social)](https://github.com/a-d-i-t-h-y-a-n/hermit-bot)
2. Scan the QR or pair and copy it
    <br>
<a href='https://hermit.adithyan.in.net/' target="_blank"><img alt='SESSION' src='https://img.shields.io/badge/SESSION-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=black'/></a>

#### DEPLOY TO RENDER 

1. If You don't have a account in render. Create a account.
    <br>
<a href='https://dashboard.render.com/register' target="_blank"><img alt='render' src='https://img.shields.io/badge/-Create-black?style=for-the-badge&logo=render&logoColor=white'/></a>

3. Get [DATABASE_URL](https://github.com/A-d-i-t-h-y-a-n/hermit-md/wiki/DATABASE_URL) and copy it

4. Get [Render api key](https://dashboard.render.com/u/settings#api-keys)

2. Now Deploy
    <br>
<a href='https://render.com/deploy?repo=https://github.com/A-d-i-t-h-y-a-n/hermit-md' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-DEPLOY-black?style=for-the-badge&logo=render&logoColor=white'/></a>

#### DEPLOY TO KOYEB 

1. If You don't have a account in koyeb. Create a account.
    <br>
<a href='https://app.koyeb.com/auth/signup' target="_blank"><img alt='koyeb' src='https://img.shields.io/badge/-Create-black?style=for-the-badge&logo=koyeb&logoColor=white'/></a>

3. Create [DATABASE_URL](https://app.koyeb.com/database-services/new) and copy it

4. Get [Koyeb API_KEY](https://app.koyeb.com/settings/api)

2. Now Deploy
    <br>
<a href='https://hermit.adithyan.in.net/koyeb' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-DEPLOY-black?style=for-the-badge&logo=koyeb&logoColor=white'/></a>

#### RUN ON VPS/UBUNTU/WINDOWS

1. Install NodeJs,ffmpeg
2. Installation
   ```
   npm i -global pm2
   git clone https://github.com/A-d-i-t-h-y-a-n/hermit-md.git
   cd hermit-md
   npm install
   ```
3. Configuration
   ```
   echo "VPS = true
     SESSION_ID = null
     AUTH_FILE = session
     SUDO = null
     PREFIX = .
     MODE = private
     LOG_MSG = true" > config.env
   ```
- Start
  ```
  npm start
  ```
- Stop
  ```
  pm2 delete hermit-md
  ```
<br>

For help visit [Github wiki](https://github.com/A-d-i-t-h-y-a-n/hermit-md/wiki)

***

[![Join us on Telegram](https://img.shields.io/badge/Join_Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/hermitmd_official)

<a href="https://whatsapp.com/channel/0029Va4OxFAGk1FjrFvTJa1V"><img alt="WhatsApp" src="https://img.shields.io/badge/-Whatsapp%20Channel-white?style=for-the-badge&logo=whatsapp&logoColor=black"/></a>
