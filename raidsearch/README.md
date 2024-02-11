# RaidSearch v1.0.0

A tool to help you find a raid target for your channel. Or let the chat choose! Features include:

- Creating a list of potential raid targets
- Generating that list by searching for a game or category
- Manual addition of raid targets
- Create a poll to let chat choose the raid target

**Note: I don't have affiliate, so I cannot create polls, so those features are untested. They may work, but please let me know if they don't!** [(insert subtle plug here)](https://twitch.tv/mosadie)

1. Copy the import string from [raidsearch-toy.txt](./raidsearch-toy.txt)
2. Go to your Streamer.bot instance
3. Click the "Import" button in the top left
4. Paste the import string into the top text box
5. Click "Import" to import the toy into your Streamer.bot instance

## Commands

These message can be sent in chat or whispered directly to the bot. The shortest alternate form is listed in parentheses next to the command.

### !raidsearch (!rs)

Search for the top 5 streamers in a category. *Will clear the raid list.*

### !addraid \<username\>

Add a streamer to the raid list.

### !clearraidlist

Clear the raid list.

### !raidpoll

Create a poll to let chat choose the raid target. If the "Raid Poll Finish" action is enabled, it will automatically start the raid once the poll finishes.

### !raidlist (!rl)

List the current raid list.

### !raid \<raidlist id or username\>

Raid the specified streamer from the raid list. Supports raid list IDs or usernames.