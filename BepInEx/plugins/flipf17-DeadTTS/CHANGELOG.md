# 1.0.10
+ Moved some logs to verbose-only to avoid spoiling player deaths in the console.

# 1.0.9
+ When you are dead, you should see the TTS over your own head again.
+ Made some tweaks to hopefully prevent errors with player's voices sometimes not reverting to normal upon reviving.

# 1.0.8
+ Quick fix to prevent dead players' eyes from overriding any default eye flashing behaviour while they are not speaking.

# 1.0.7
+ Eyes now flash while dead players are speaking via TTS.
+ When enabling dead TTS once players are "discovered", all players should now be able to hear the dead players' TTS instead of just the one who discovered them.
+ Dead TTS should work regardless of a player's "discovered" state on the Shop level, and other secondary stages.

# 1.0.5
+ Fixed bug that prevented the pitch of dead players' TTS from randomizing.
+ Fixed bug where "discovered" dead players were remaining discovered, even in future deaths.

# 1.0.4
+ Dead TTS text color will now appear red. Configurable in the config.
+ Added config option to only hear TTS from dead players if their head has been "discovered" first. This is client-side.
+ Other minor tweaks.

# 1.0.3
+ Added config option to disable the dead TTS audio from playing at dead players' heads while you are also dead. TTS will still appear at their heads. (would behave more vanilla like in this respect)
+ Updated mod icon to be higher res.

# 1.0.2
+ Tweaked the min and max pitch for the TTS for dead players. The min was previously 0.1, but I didn't realize how broken it sounded with any pitch below 0.5.
+ The new min pitch is 0.5, and the max pitch remains at 2.0, but will default to 1.5 when generating a new config.

# 1.0.1
+ Fixed typo that caused the TTS pitch for dead players to not sync up properly.

# 1.0.0
+ Changed the lower limit for TTS volume in the config for dead players to 0, to effectively mute them while still displaying their TTS text.
+ Removed the config for the TTS audio pitch for dead players, and replaced with a lower and upper range.<br>
Each player will now have a random pitch for each level based on the min and max pitch in the config. Pitch may not always sync up perfectly between players if players have differing min/max pitch values.

# 0.1.2
+ Minor tweaks

# 0.1.1
+ The text UI for TTS of dead players should properly disappear with distance as normal.

# 0.1.0
+ Release