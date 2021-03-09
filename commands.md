# Helix command  and modules list
* 
## ⚙️ Administration
| Command | Aliases | Description | Args | Example |
| ------- | :-----: | ----------- | :--: | ------- |
|`setadminrole`|`setadminr`, `sarole`|Sets the `admin` role for your server.|`@role`|`x sarole @admin`|
|`setautorole`|`setaur`|Sets a role to give to new members.|`@role`|`x setaur @member`|
|`setmuterole`|`setmute`|Sets the muted role for the server.|`@role`|`x setmute @muted`|
|`setmodrole`|`smr`|Sets the mod role for the server.|`@role`|`x smr @mod`|
|`autokick`|none|Sets the number of warnings a user must have before being kicked.|`{number}`|`x autokick 3`|
|`setmodchannels`|`smcs`, `setmcs`|Sets a channel where only moderation commands can be used.|`#channel`|`x smcs #moderator-only`|
|`setstarboardchannel`|`sstc`|Sets a channel where starred messages will be posted.|`#channel`|`x sstc #starboard`|
|`setsystemchannel`|`ssc`|Sets a channel for Helix updates **/** important messages|`#channel`|`x ssc #helix-channel`|
|`setprefix`|`sp`, `setp`|Sets Helix's prefix for the server.|`{new prefix}`|`x sp !`|
|`config`|`settings`, `conf`|Helix's configuration for the server.|none|`x conf`|
|`togglecommand`|`tc`, `togc`|Disables **/** enables a given command.|`{command name}`|`x tc meme`|
|`toggletype`|`togt`, `tt`|Disables **/** enables a given module.|`{module}`|`x tt fun`
|`togglerc`|`trc`|Disables **/** enables giving a random color role to a member.|none|`x trc`|

* 
## 🛠️ Moderation
| Command | Aliases | Description | Args | Example |
| ------- | :-----: | ----------- | :--: | ------- |
|`ban`|-|Bans given user.|`@user` / `ID` + `[reason]`|`x ban @user spamming`|
|`softban`|-|Bans a user then unbans them.|`@user` / `ID` + `[reason]`|`x softban @user spamming`|
|`kick`|-|Kicks given user.|`@user` / `ID` + `[reason]`|`x kick @user spamming`|
|`mute`|-|Mutes given member.|`@user` / `ID` + `<time>` + `[reason]`|`x mute @user 5m spamming`|
|`warn`|-|Warns given user|`@user` / `ID` + `[reason]`|`x warn @user spamming`|
|`clearwarns`|-|Clears a given user's warns.|`@user` / `ID` + `[reason]`|`x clearwarns @user being good`|
|`addrole`|`giverole`, `ar`|Gives a user a role.|`@user` / `ID` + `@role` / `ID`|`x ar @user @member`|
|`removerole`|`remover`, `rr`|Removes a role from a user.|`@user` / `ID` + `@role` / `ID`|`x rr @user @member`|
|`purge`|`clear`|Deletes up to 1000 messages.|`#channel` + `@user` + `{number}`|`x purge #general @user 10`|
|`unban`|-|Unbans given user.|`@user` / `ID` + `[reason]`|`x unban @user being good`|
|`unmute`|-|Unmutes given user.|`@user` / `ID` + `[reason]`|`x unmute @user being good`|
|`warns`|-|Lists the number of warns of a user|`@user` / `ID`|`x warns @user`|
|`slowmode`|`sm`|Sets a slowmode on the given channel.|`#channel` + `{number(in_seconds)}`|`x slowmode #general 600`|
|`setnickname`|`snn`|Sets a nickname for a user|`@user` + `{new nickname}`|`x snn @user Coconut Man`|

## more of the commands coming on the page soon!

![soup](https://media.discordapp.net/attachments/747111170543976457/815333146870284298/trustandsafety.png "E")

### Other Links

* Support server : [🧭](https://discord.gg/GapmaCt)
* Invite link : [🧭](https://discord.com/oauth2/authorize?client_id=723697439638290482&scope=bot&permissions=1056304374)
