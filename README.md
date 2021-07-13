# SPAM Bam  Telegram
Spam Bam Telegram is a Telegram bot that bans spammers who DM defi users in need of support.

The bot acts like a honeypot. 

1. Bot posts a message in a telegram group requesting help.
2. Scammer user sends DM to bot user pretending to be group support.
3. Bot scans for keywords in message and scammer username and creates a scammer rating.
4. If scammer rating is greater than x then kick the scammer user from the group.
5. If the same scammer user rejoins the group and repeats the same behaviour 3 times then ban the user from group.

## Bot behaviour 

- engage the scammer in a conversation in order to bait them to ask the bot to provide their wallet key or to visit an external url
- the bot could post a message in the telegram bot at regular intervals throughout the day to bait the scammer
- the bait message could be from be from a list of randomised canned messages.
- the canned messages could be defined by the tg group admins.
