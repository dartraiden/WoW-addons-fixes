# My fixes to the addons I use

## [BugGrabber](https://www.curseforge.com/wow/addons/bug-grabber)
* nospam.patch — silence the plugin: no errors output to chat, no "There are too many errors in your UI" message, no reminder about /stopnag

## [ChatBar Classic](https://www.curseforge.com/wow/addons/chatbar-classic)
* C_GuildInfo.CanEditOfficerNote.patch — CanEditOfficerNote() is deprecated since 8.2 and removed in 9.0.1
* inherite_BackdropTemplate.patch — starting from 9.0.1, no frames have backdrops unless the addon imports/inherits the backdrop template

## [Data Broker Volume Control](https://www.wowace.com/projects/data-broker-volume-controle)
* ActionStatusDisplayMessage.patch — ActionStatus_DisplayMessage was replaced by ActionStatus:DisplayMessage in 9.0.1
* inherite_BackdropTemplate.patch — starting from 9.0.1, no frames have backdrops unless the addon imports/inherits the backdrop template

## [Handynotes - Warfront Rares](https://www.curseforge.com/wow/addons/handynotes-warfrontrares)
* IsQuestFlaggedCompleted.patch — IsQuestFlaggedCompleted is deprecated since 8.2.5 and removed in 9.0.1

## [MTLove2](https://www.curseforge.com/wow/addons/mtlove-2)
* fix_sound.patch —  starting from 7.3.0, string-based input is not allowed for PlaySound
* GetRealmName.patch — GetCVar("realmName") was removed in 5.4.1 and should be replaces by GetRealmName()
* inherite_BackdropTemplate.patch — starting from 9.0.1, no frames have backdrops unless the addon imports/inherits the backdrop template
* nospam.patch — stop spamming chat at login
* UnitIsTapDenied.patch — UnitIsTapped() was removed in 7.0.3 and should be replaces by UnitIsTapDenied()