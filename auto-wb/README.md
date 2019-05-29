# auto-wb v1.0.0

#### To make it easier to add the files, go to releases and download the latest zip. Then, copy the required txt files to \liteconfig\common\macros. They should appear in game. 

### Macro bindings
##### (changes in bold) (read CHANGELOG.md for complete changes)

* bind this to onJoinGame: $${UNSET(@afk);LOG(UNSET AFK)}$$
* bind this to onPlayerJoined: $${IIF(@afk=0, wb)}$$
* bind <isnotafk.txt> to onChat
* bind <isafk.txt> to onSendChatMessage
* replace (.*) \[Royal Guard of the King\]~Fili is no longer AFK with your name and tag in isnotafk.txt




