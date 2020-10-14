# My fixes to the addons I use

## BugGrabber
* nospam.patch — silence the plugin: no errors output to chat, no "There are too many errors in your UI" message, no reminder about /stopnag

## MTLove2
* fix_sound.patch —  starting from 7.3.0, string-based input is not allowed for PlaySound
* GetRealmName.patch — GetCVar("realmName") was removed in 5.4.1 and should be replaces by GetRealmName()
* inherite_BackdropTemplate.patch — starting from 9.0.1, no frames have backdrops unless the addon imports/inherits the backdrop template
* nospam.patch — stop spamming chat at login
* UnitIsTapDenied.patch — UnitIsTapped() was removed in 7.0.3 and should be replaces by UnitIsTapDenied()