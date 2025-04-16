# MCPServer-GitHUb-Slack-Integration
MCPServer-GitHUb-Slack-Integration
Setup
Create a Slack App:

## Visit the Slack Apps page
Click "Create New App"
Choose "From scratch"
Name your app and select your workspace

## Configure Bot Token Scopes: Navigate to "OAuth & Permissions" and add these scopes:

channels:history - View messages and other content in public channels

channels:read - View basic channel information

chat:write - Send messages as the app

reactions:write - Add emoji reactions to messages

users:read - View users and their basic information

channels:join - To join channels



## Step : Invite the bot to the Slack channel

Open your Slack workspace and navigate to the #itascode-devsecops-cloud channel
In the message field at the bottom of the channel, type the following command:
/invite @Claude
(Replace "Claude" with the actual name of the bot if it's different)
Press Enter to execute the command
You should see a confirmation message that the bot has been added to the channel

## Install App to Workspace:

Click "Install to Workspace" and authorize the app
Save the "Bot User OAuth Token" that starts with xoxb-
Get your Team ID (starts with a T) by following this guidance
