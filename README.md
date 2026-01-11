<h1 align="center"><b> 🕊️⃝‌ᴘʙx ❤️ᥫ᭡፝֟፝֟ 2.0</b></h1>

<p align="center"><img src="https://telegra.ph/file/fd8a6715f04182086b49e.jpg" alt="Badhacker98"></p>

<h2 align="center">😈 Telegram Bot on Steroids!</h3>

<h3 align="center">
    ᴀ sᴍᴏᴏᴛʜ ☆ ғᴀsᴛ ᴛᴇʟᴇɢʀᴀᴍ ᴜsᴇʀʙᴏᴛ 
☆ ᴀᴅɴᴀᴄᴇ ғᴇᴀᴛᴜᴇʀs
</h3>

---

![GitLab forks](https://img.shields.io/gitlab/forks/Badhacker98/PBX_2.0?style=social)
![GitLab Repo stars](https://img.shields.io/gitlab/stars/Badhacker98/PBX_2.0?style=social)

![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-white?&style=social&logo=hugo)
![GitLab license](https://img.shields.io/gitlab/license/Badhacker98/PBX_2.0?&style=social&logo=gitlab)


[![Telegram Group](https://img.shields.io/badge/Telegram-Group-white?&style=social&logo=telegram)](https://t.me/ll_THE_BAD_BOT_ll)
[![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-white?&style=social&logo=telegram)](https://t.me/PBX_NETWORK)



---

## Deploying PBXBOT 2.0 on Heroku

Follow these 4 straightforward steps to deploy PbxBot on Heroku:

1. **Fork & Star this Repo:**
    > Begin by [forking](https://gitlab.com/Badhacker98/PBX_2.0/-/forks/new) and [starring](https://gitlab.com/Badhacker98/PBX_2.0) this repository on GitLab.

2. **Heroku Account Login:**
   > Ensure you are logged into your [Heroku account](https://dashboard.heroku.com) before proceeding.

3. **Click "Deploy to Heroku":**
   > Find the "Deploy to Heroku" button below, and click it, but make sure you are deploying from your fork.

4. **Fill Required Variables:**
   > On the deployment page, you'll find necessary variables to be filled out.

That's it! You've successfully deployed Pbx  on Heroku. Now scale dynos and start the bot!

<p align="center">
    <a href="https://heroku.com/deploy"><img src="https://img.shields.io/badge/Pbxbot-Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku"/></a>
</p>

---

## Deploy To Render ⚠️ Deploy On EU Server

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://gitlab.com/Badhacker98/PBX_2.0)

---

## Deploying PBXBOT 2.0 on Linux

Pbxbot 2.0 can be deployed on any Linux VPS and terminal.

1. **Update Packages:**   
    ```bash
    sudo apt update && sudo apt upgrade -y
   ```

2. **Install required packages:**
    ```bash
    sudo apt install --no-install-recommends -y python3 python3-dev python3-pip python3-virtualenv git mediainfo nano ffmpeg unzip tmux
    ```

3. **Clone GitLab repository:**
   ```bash
   git clone https://github.com/PbxBad/PbxPlugin && cd PbxPlugin
   ```

4. **Edit Config Variables:**
   ```bash
   cp example.env .env && vi .env
   ```
   > Now press 'i' on your keyboard to start editing the .env file.
   
   > Now fill all the env mentioned in the file.
   
   > To save the file press 'Esc' button and write ':wq' using your keyboard and press 'Enter'

5. **Install Requirements:**
    > Create an virtualenv and source it.
    ```bash
    python3 -m virtualenv venv && source venv/bin/activate
    ```
    > Now install requirements but make sure you're in (venv)
    ```bash
    pip3 install -U -r requirements.txt
    ```

6. **Start the Bot:**
    > Start a sub-terminal using tmux
    ```bash
    tmux new-session -s PBXBOT2.0
    ```
    > Now start the bot
    ```bash
    chmod +x ./start.sh && ./start.sh
    ```
    > Not press 'Ctrl + B' then 'D' to detatch from tmux and let your bot run in background.

That's it! You've successfully deployed Pbxbot 2.0 on a Linux VPS in 6 easy steps.

---

## Config Variables

- **API_HASH** : _Get this value from [my.telegram.org](https://my.telegram.org)_

- **API_ID** : _Get this value from [my.telegram.org](https://my.telegram.org)_

- **BOT_TOKEN** : _Get this value from [@Botfather](https://telegram.dog/BotFather)_

- **DATABASE_URL** : _Get this value from [mongo.db](https://account.mongodb.com/account/login)_

- **LOGGER_ID** : _A group/channel id to use as a logger chat._

- **OWNER_ID** : _The owner of bot. Only single userid is supported._

> More config details coming soon with updated documentations

---


# License

This project is licensed under the [MIT License](https://gitlab.com/Badhacker98/PBX_2.0/-/blob/main/LICENSE) —  
Feel free to use, modify, and share it with credit. ❤️

---

<h2 align="center">
  Made with ❤️ by <a href="https://gitlab.com/Badhacker98">🕊️⃝‌ʙᴀᴅ ❤️ᥫ᭡</a>
</h2>
