# DFOAlert
Simple tool to alert when an Outpost Attack started in Dead Frontier 3D game.

# How does it works?

A loop will be scanning for Outpost Attacks every 3 seconds, then, when the DFOA API returns something, it will then start a 
countdown of 20 minutes. (or the remaining time left) It will then keep scanning to see if the event has ended.

# Why not just use the Discord bot?

Because the Discord bot is not precisely enough and because I'm not always on Discord. This tool is accessing DF3D's API directly 
and displaying the real deal.
