# Motivation

Scaler has hosted many challenges like 30-days-of-code, code-everyday, open-source-september on its Discord server where participants have to post daily about their progress on Discord and/or Twitter/LinkedIn. After the challenge ends, admins/Scaler stars verify who is eligible for rewards reviewing the posts manually.
Manual verification takes a lot of time! Verification can be automated and done faster using a Discord bot.


## Important Note
This is a more open ended problem statement which essentially requires you to come up with an idea, where you have to use Discord API and build a discord bot that could potentially help automate some of the verification process for some activities/challenges like 30 days of code, where everyday, users participating post about their completion and the bot can take keep a track if a user is making post daily. 
If the user doesn't make a post daily it can automatically count that user as ineligible for a prize. 

## Some things you can consider for the bot - Note these are not mandatory and you can think of your own implenentation: 

- Participants will either tag the bot or use bot command when sending their message on Discord linking their tweet or LinkedIn post. This will invoke the bot and store user's entry for that day.
- If a user misses a day, bot will automatically show that he/she is out of the challenge.
- Bot could also have a functionality where it will parse the tweet or LinkedIn post and check whether the format is correct (proper hashtag used, screenshot attached, etc. ). If a user posts in wrong format it will warn user to correct the format. It will save participant's streak.
- After the challenge ends, moderators can filter out entries according to eligible (for rewards) or ineligible tag set by bot automatically for each user.
- Mods will have to verify posts only out of eligible entries thereby reducing time and effort!
- Export to PDF or doc feature to share list of eligible participants in Discord.
- A tokens distributing feature where tokens for eligible participants will be added in a single click after adding relevant permission to bot to use this feature.

 
## Key benefits
- Reduced time and effort for mods.
- Faster delivery of rewards to participants.
