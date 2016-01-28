# NadekoBot Admin Only

Nadeko Discord chatbot written in C# using Discord.net library.  
You might want to join Kwoth's discord server where Kwoth and I can provide help etc. https://discord.gg/0ehQwTK2RBhxEi0X

#### If you want to semi-easily setup the bot, go to [releases](https://github.com/ZR2/NadekoBot-Admin/releases)

### Administration  
Command and aliases | Description | Usage
----------------|--------------|-------
`-h`, `-help`, `@BotName help`, `@BotName h`  |  Help command
`.sr`, `.setrole`  |  Sets a role for a given user. |  .sr @User Guest
`.rr`, `.removerole`  |  Removes a role from a given user. |  .rr @User Admin
`.r`, `.role`, `.cr`  |  Creates a role with a given name, and color. |  .r AwesomeRole Orange
`.rc`, `.color`  |  Set a role's color to the rgb(0-255 0-255 0-255) color value provided. |  .color Admin 255 255 255
`.b`, `.ban`  |  Bans a mentioned user
`.ub`, `.unban`  |  Unbans a mentioned user
`.k`, `.kick`  |  Kicks a mentioned user.
`.rvch`  |  Removes a voice channel with a given name.
`.vch`, `.cvch`  |  Creates a new voice channel with a given name.
`.rch`, `.rtch`  |  Removes a text channel with a given name.
`.ch`, `.tch`  |  Creates a new text channel with a given name.
`.st`, `.settopic`  |  Sets a topic on the current channel.
`.uid`, `.userid`  |  Shows user id
`.cid`, `.channelid`  |  Shows current channel id
`.sid`, `.serverid`  |  Shows current server id
`.stats`  |  Shows some basic stats for nadeko
`.leaveall`  |  Nadeko leaves all servers
`.prune`  |  Prunes a number of messages from the current channel. |  .prune 50
`.die`  |  Works only for the owner. Shuts the bot down.
`.clr`  |  Clears some of nadeko's messages from the current channel.
`.newname`  |  Give the bot a new name.
`.setgame`  |  Sets the bot's game.**Owner only**.
`.greet`  |  Enables or Disables anouncements on the current channel when someone joins the server.
`.greetmsg`  |  Sets a new announce message. Type %user% if you want to mention the new member. |  .greetmsg Welcome to the server, %user%.
`.bye`  |  Enables or Disables anouncements on the current channel when someone leaves the server.
`.byemsg`  |  Sets a new announce leave message. Type %user% if you want to mention the new member. |  .byemsg %user% has left the server.
`.checkmyperms`  |  Checks your userspecific permissions on this channel.
`.commsuser`  |  Sets a user for through-bot communication. Only works if server is set.**Owner only**.
`.commsserver`  |  Sets a server for through-bot communication.**Owner only**.
`.send`  |  Send a message to someone on a different server through the bot.**Owner only.**
  |  .send Message text multi word!
