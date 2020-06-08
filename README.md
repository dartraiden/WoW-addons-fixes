# My fixes to the addons I use

## BugGrabber
* nospam.patch — silence the plugin: no errors output to chat, no "There are too many errors in your UI" message, no reminder about /stopnag

## MTLove2
* GetRealmName.patch — GetCVar("realmName") was removed in 5.4.1 and should be replaces by GetRealmName()
* nospam.patch — stop spamming chat at login
