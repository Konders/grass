# Grass Auto Reger&Farm 🔹


Discover the latest `<crypto/>` moves in my Telegram Channel:

[![My Channel 🥰](https://img.shields.io/badge/Web3_Enjoyer_|_Subscribe_🥰-0A66C2?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/web3_enjoyer_club) 

Cheapest [proxies and servers](https://teletype.in/@web3enjoyer/4a2G9NuHssy) which fits for  on [grass.io](https://app.getgrass.io/register/?referralCode=erxggzon61FWrJ9).

![image](https://github.com/MsLolita/grass/assets/58307006/610b95b4-369f-4a71-ac24-f45e8dee6380)


### What is bot for?
   - Create Accounts
   - Farm Points
   - Check Points
   - Approve Emails without access to it (no need imap, etc)

> You can put as many proxies as u can, bot uses database and will load up proxies from extra ones

🔹**To say thanks for work: 0x000007c73a94f8582ef95396918dcd04f806cdd8**


## Quick Start 📚
   1. To install libraries on Windows click on `INSTALL.bat` (or in console: `pip install -r requirements.txt`).
   2. To start bot use `START.bat` (or in console: `python main.py`).

### Options 📧

1. CREATE ACCOUNTS:
 - In `data/config.py` put `REGISTER_ACCOUNT_ONLY = True`
 - Throw the api key into `data/config.py`. Since there is a captcha there, you need a service for solving captchas - [AntiCaptcha](http://getcaptchasolution.com/t8yfysqmh3) or [Twocaptcha](https://2captcha.com/?from=12939391).
 - Provide emails and passwords (OPTIONAL) and proxies to register accounts as below!

  ![image](https://github.com/MsLolita/grass/assets/58307006/67740c9b-07d6-4f78-a87d-27b09c0303e8)

2. FARM POINTS:
 - in `data/config.py` put `REGISTER_ACCOUNT_ONLY = False`
 - Provide emails and passwords and proxies to register accounts as shown below!

3. APPROVE EMAILS:
 - in `data/config.py` put `APPROVE_EMAIL_ONLY = True`
 - Provide emails and passwords and proxies as always (as shown below)!
 - No imap or email access required.

### Configuration 📧

1. Accounts Setup 🔒

   Put in `data/accounts.txt` accounts in format email:password (cool_aster@gmail.com:my_password123)
   
   ![image](https://github.com/MsLolita/grass/assets/58307006/2f8bacaa-0212-49fe-b362-fe764230f47c)

2. Proxy Setup 🔒

   Configure your proxies with the *ANY* (socks, http/s, ...) format in `data/proxies.txt` 🌐

   ![Proxy Configuration](https://github.com/MsLolita/VeloData/assets/58307006/a2c95484-52b6-497a-b89e-73b89d953d8c)

## Quick Start By Docker
   1. Install Docker-CE: `curl -sSL -k https://get.docker.com | sh`
   2. Install Docker Compose: `curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose && chmod +x /usr/local/bin/docker-compose`
   3. Clone Source Code: `git clone https://github.com/MsLolita/grass.git`
   4. Configuration: Modify `data/accounts.txt` and `data/proxies.txt`
   5. Start Container: `docker-compose up -d`

   PS: Could see more configuration in `docker-compose.yml`

