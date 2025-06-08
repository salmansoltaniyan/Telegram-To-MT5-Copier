Telegram Signal EA - Real-time Signal Display on MT5 Charts
=====================================================

Abstract:
--------
TelegramToMT5 is a MetaTrader 5 Expert Advisor that bridges Telegram and MT5 by displaying messages from your Telegram channels, groups, and private chats directly on your trading charts. Simply create a Telegram bot, add it to your desired channels/groups, and let the EA show all messages as comments on your chart in real-time.

Description:
-----------
Telegram Signal EA is a powerful tool that allows you to display messages from Telegram channels, groups, and private chats directly on your MetaTrader 5 charts as comments. This EA acts as a bridge between your Telegram communications and MT5, making it easier to monitor trading signals and messages while trading.

Features:
--------
- Display messages from Telegram channels, groups, and private chats
- Real-time updates with configurable check interval
- Clear message formatting with proper spacing
- Support for channel posts, group messages, and private chats
- Automatic message processing and display
- Easy-to-read comment format on charts

Installation Steps:
-----------------
1. Create a Telegram Bot:
   a. Open Telegram and search for "@BotFather"
   b. Start a chat with BotFather
   c. Send the command "/newbot"
   d. Follow the prompts to:
      - Choose a name for your bot
      - Choose a username (must end in 'bot')
   e. BotFather will provide you with a bot token (keep this secure)

2. Configure Bot Privacy:
   a. In BotFather, send the command "/mybots"
   b. Select your bot
   c. Click "Bot Settings"
   d. Click "Group Privacy"
   e. Click "Turn off" to disable privacy mode
   f. Click "Back" and then "Done"

3. Add Bot to Groups/Channels:
   a. For Groups:
      - Open the group
      - Click group name
      - Click "Add members"
      - Search for your bot
      - Add the bot as an administrator
   
   b. For Channels:
      - Open the channel
      - Click channel name
      - Click "Administrators"
      - Click "Add Admin"
      - Search for your bot
      - Add the bot as an administrator

4. Configure MetaTrader 5:
   a. Open MetaTrader 5
   b. Go to Tools -> Options -> Expert Advisors
   c. Check "Allow WebRequest for listed URL"
   d. Add "api.telegram.org" to the allowed URLs
   e. Click OK to save settings

5. Install the EA:
   a. Copy the EA files to your MT5 directory:
      - TelegramToMT5.mq5 to MQL5/Experts/
      - Telegram.mqh to MQL5/Include/
      - jason.mqh to MQL5/Include/
      - Common.mqh to MQL5/Include/
   b. Restart MetaTrader 5
   c. Open the Navigator window (Ctrl+N)
   d. Find the EA under "Expert Advisors"
   e. Drag and drop it onto your chart

6. Configure the EA:
   a. In the EA settings, enter your bot token
   b. Set the update interval (default: 1 second)
   c. Click OK to start the EA

Usage:
-----
1. The EA will automatically start displaying messages from your Telegram channels, groups, and private chats on your chart
2. Messages are displayed as comments with proper formatting and spacing
3. Each message includes:
   - Source information (channel/group/private chat)
   - Sender details (for groups and private chats)
   - Message content
   - Timestamp

Troubleshooting:
--------------
1. If messages are not appearing:
   - Verify your bot token is correct
   - Check if the bot is added to the group/channel
   - Ensure privacy mode is disabled
   - Verify api.telegram.org is in the allowed URLs list
   - Ensure all required files are in the correct directories

2. If you see "Failed to initialize" error:
   - Check your internet connection
   - Verify the bot token
   - Ensure the EA has proper permissions
   - Verify all required files are present

3. If messages are delayed:
   - Adjust the update interval in EA settings
   - Check your internet connection speed

Support:
-------
For support, please visit: https://www.mql5.com/en/users/salmansoltaniyan
To post a job request: https://www.mql5.com/en/job/new?prefered=salmansoltaniyan

License:
-------
This software is licensed under the MIT License. See the license section in the code for details.

Author:
------
Salman Soltaniyan
https://www.mql5.com/en/users/salmansoltaniyan 