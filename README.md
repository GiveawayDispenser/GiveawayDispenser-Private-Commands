**Private Settings/Commands**
>These commands must be whispered directly to the bot, and do not provide responses via whisper if any.  Only streamers can access these commands.
- ![](broadcaster%20icon.png "Broadcaster") <kbd>setoauth _oauthkey_</kbd> - Sets the oauth key that the bot will need in order to fetch certain information about the stream and users in it.
- ![](broadcaster%20icon.png "Broadcaster") <kbd>setclientid _clientid_</kbd> - Sets the client id that the bot will need in order to fetch certain information about the stream and users in it.
- ![](broadcaster%20icon.png "Broadcaster") <kbd>setdiscordkey _discordwebhook_</kbd> - Sets the discord webhook which is required in order for the bot to output all the rolls upon a giveaway being finalized.
- ![](broadcaster%20icon.png "Broadcaster") <kbd>setdiscordkey2 _discordwebhook2_</kbd> - Sets the discord webhook #2 which is required in order for the bot to output bot log files.  Probably make this discord channel private.
- ![](broadcaster%20icon.png "Broadcaster") <kbd>setoverflow _amount_</kbd> Entering an amount will make it so when someone wins a giveaway and their currency amount was over 100, the amount over 100 is kept, otherwise all currency is lost after u win. Setting the amount to 0 disables this feature.
- ![](broadcaster%20icon.png "Broadcaster") <kbd>setgiveawaymsg _giveaway message_</kbd> Changes what you are giving away upon starting the giveaway. What are you giving away? Default: a FREE KEY
- ![](broadcaster%20icon.png "Broadcaster") <kbd>settimermsg _msg_</kbd>  This is the chat message that announces that the giveaway is still open. Default: a FREE KEY!
- ![](broadcaster%20icon.png "Broadcaster") <kbd>settimerdelay _delay_in_seconds_</kbd> Use this to change the delay between the announcement that there is still a gvieaway in progress. Default: 45
- ![](broadcaster%20icon.png "Broadcaster") <kbd>settimerenabled _0 or 1_</kbd> This will enable (1) or disable (0) the announcement of a giveaway in progress. Default: enabled (1)
- ![](broadcaster%20icon.png "Broadcaster") <kbd>enablebot _0 or 1_</kbd> This will enable(1) or disable(0) the bot from accepting commands or keywords from chat.  Default: enabled(1)
- ![](broadcaster%20icon.png "Broadcaster") <kbd>sendlog</kbd>  This will send the current bot log file to discord webhook #2.  This can be helpful for example in determining if someones claim to not getting their currency has any merrit, or just basic troubleshooting/analysis.
