# LurkerBotBanner
Currently a list of Twitch lurker bots.

The eventual goal is to create a python script that could be used with Streamlabs Chatbot. The script would be loaded into the Chatbot, have a command tied to it, which would execute the script. The script would reference the list of lurker bots, and issue /ban commands per user in the list.

Due to Twitch not having any API commands to issue a ban, this is the only "automated" solution that comes to mind at the moment.

Currently I am resourcing https://twitchinsights.net/bots for a list - with the slight modification of removing the bots that users put into their channel (like Nightbot, Moobot, etc).
