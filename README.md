# My PC Remote

The Discord PC Control Bot allows you to remotely manage your PC using custom Discord commands. With this bot, you can execute various actions on your computer from anywhere with an internet connection, all through Discord.

## Available Commands

- **Beep** Generate beep sound from speakers.
- **Camera Frame** Capture frames from your PC's camera.
- **Grab Screenshots** Capture screenshots of your PC's desktop.
- **Hybernate** Hybernate your PC
- **Kill App** Terminate the specific running application
- **Location** Extract current location using IP address and show it in MAP
- **Lock** Locks the OS same as doing WIN + L in windows
- **Notification** Show a notification to user e.g. Message box or Windows 10/11 Toast
- **Launch URL** This will open the URL in default browser
- **Ping** This will initiate a PING command to check connectivity status & latency
- **Reboot** This will reboot the Computer
- **Shutdown** This will power of the computer
- **Sleep** This will initiate a computer sleep
- **Speak** This is a TTS (Text to Speach) command speak provided sentence in speakers
- **Status** This will publish the current computer status e.g. Processor and ram usage
- **Terminal** This command will let you execute any terminal command and return the results
- **Terminate** This will terminate the bot hence no more commands will be executed remotely
- **Upload** This will let you upload a file into remote location specified in the command
- **Voice Call** This will initiate a live call in the call channel so you can listen to the MIC (Live Audio SPY)
- **Volume** This will set/return the Speakers volume

## Setup the Bot
First install the BOT as a package using `pip3 install mypcremote`
To use the bot your need to have a Discord application Auth Token, Create your discord application using [Discord Developer Portal](https://discord.com/developers/applications), Copy the TOKEN, grant all required INTENTS to the application you created, Finally run the bot by typing command `mypcremote` enter the copied token when asked and you are done:

Use [this](https://discordapi.com/permissions.html) URL to define or configure your custom bot application permissions

## Test the Bot
If everything is setup good then after running, The bot will send a greeting message in the channel where you joined the bot application. Use # to call the commands if you are unclear about command use #help to check for available commands.

- **#camera**: Capture a frame from the PC's camera.
- **#screenshot**: Capture a screenshot of the PC's desktop.

## Disclaimer
This project is for educational and experimental purposes only. Use it responsibly and at your own risk.

## License
This project is licensed under the [MIT License](LICENSE).