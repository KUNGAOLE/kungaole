Computer Software Requirements Document

Website Crawler for Information Analysis:

Needs to scrape a certain website, specifically identifying the first section of lottery number information.
The data should be read every 5 minutes and sent back to a WeChat auto-reply bot.
WeChat Auto-Reply Bot:

Should reply with relevant information, like confirmation messages, whenever a user types something.
At the end of each cycle, it should send out the corresponding lottery numbers, publish related data tables showing user information, current amounts, etc.
Allows operations within the cycle when a user withdraws, and performs calculations based on the user's information script.
If a user's balance is low or they don’t have enough "bullets" to load, it should send a message about insufficient balance.
User Information Calculation Script:

When the program starts, it recognizes the first three numbers from user inputs like "1-6-7/50" and logs the last number as the current number of bullets for that user, then performs calculations based on the user information script.
After recognizing the first three numbers, it records them. When specifically identifying the first section of the lottery number information, it matches these numbers with the corresponding digits of the lottery numbers to determine if the user successfully hits the target.
Every 5 minutes, calculate a cycle and publish 10 numbers each time.
After a user inputs information, like "1-6-7/50", it should store this in the backend along with the user’s name, desired target position, and number of bullets they have.
