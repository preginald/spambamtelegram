# SPAM Bam  Thank-You Maam
Spam Bam Thank You Maam is a Telegram bot that bans spammers who DM defi users in need of support.

The bot acts like a honeypot. 

1. Bot posts a message in a telegram group requesting help.
2. Scammer user sends DM to user pretending to be group support.
3. Bot scans for keywords in message and scammer username and creates a scammer rating.
4. If scammer rating is greater than x then kick the scammer user from the group.
5. If the same scammer user rejoins the group and repeats the same behaviour 3 times then ban the user from group.
