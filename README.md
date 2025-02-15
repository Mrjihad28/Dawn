# DAWN VALIDATOR BOT
1. Download DAWN Extension: DOWNLOAD (https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp)
2. Input email dan wajib menggunakan invite code. 
3. Invite code

   ```
   s2ez0x16
   ```
5. Selesain task buat dapet tambahan 15k point
6. Stay connect biar tetep dapetin DAWN point.

# Join My Telegram Channel

___  _______________________ ___________ 
 / _ \|_   _| ___ \  _  \ ___ \  _  | ___ \
/ /_\ \ | | | |_/ / | | | |_/ / | | | |_/ /
|  _  | | | |    /| | | |    /| | | |  __/ 
| | | |_| |_| |\ \| |/ /| |\ \\ \_/ / |    
\_| |_/\___/\_| \_|___/ \_| \_|\___/\_|    
                                           
                                           
  _____ _   _______ _____                  
 |_   _| | | | ___ \  ___|                 
   | | | | | | |_/ / |__                   
   | | | | | | ___ \  __|                  
   | | | |_| | |_/ / |___                  
   \_/  \___/\____/\____/

[*MY CHANNEL*](https://t.me/AirdropTube28)

## Dawn Validator Bot with Multiprocessing Workers

## How To Use
1.  Clone Repo
    ```
    git clone https://github.com/Mrjihad28/Dawn.git
    ```
2.  Move to Directory
    ```
    cd DawnValidatorBot
    ```
3.  Install Requirements
    ```
    pip install -r requirements.txt
    ```
4.  Fill Telegram Token, Email and Bearer Token
    ```
    nano config.json
    ```

    example config for multiple accounts
    ```
    "accounts": [
    {
      "email": "YOUR DAWN VALIDATOR EMAIL",
      "token": "YOUR BEARER TOKEN"
    },
    {
      "email": "YOUR DAWN VALIDATOR EMAIL",
      "token": "YOUR BEARER TOKEN"
    }
    ```

5.  Run Bot
    ```
    # Termux
    python main.py # default 3 worker
    python main.py -w 10 # optional, 10 is amount of workers

    # Linux / CMD
    python3 main.py # default 3 worker
    python3 main.py -w 10 # optional, 10 is amount of workers
    ```
# How To Find Your Bearer Token

Right Click on Dawn Validator Extension and Choose Inspect, Choose Network Tab, and find BEARER TOKEN there

