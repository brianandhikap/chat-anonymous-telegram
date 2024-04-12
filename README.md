1. Clone repository:
   ```bash
   git clone https://github.com/brianandhikap/chat-anonymous-telegram
   
2. Install atau upgrade
   ```bash
   $ pip install python-telegram-bot --upgrade

3. Edit config.py (ADMIN_ID dan BOT_TOKEN)
    ```python
    # config.py

    BOT_TOKEN = "Token_Bot_Mu"
    ADMIN_ID = "ID_Telegram_mu"

4. Kembangkan sendiri bot mu di bot.py dan my_data.py
 
6. Running botnya:
   ```bash
   python bot.py

Command di bot yang tersedia:

    /start - start bot
    /chat -  cari lawan bicara
    /exit - keluar dari chat
    /newchat - keluar dari chat dan mencari yang lainnya
    /stats - lihat statistics (cuman admin)
