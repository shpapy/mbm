# mbm
MBM - Multi Bot Maintainer

The MBM is a script to maintain order with several bots running https://github.com/PokemonGoF/PokemonGo-Bot at a time.
Its designed to run as "brainless" as possible, doing the thinking while you can concentrate on other things.

It is designed to react on circumstances relevant to the Bot. We are building on a "Sick" detection, or will restart the bot if it crashed.

It is suggested to run the script as cronjob every 15 minutes if the manual execution satisfied you.

# Thanks

Big thanks to

viruz82 - Hes driving along with the whole idea and is my main contributor

# How do I run?

Check the Wiki plx

# ToDo list

* Split up configs to have one main config and several per bot unique configs combined
* Add more detections for invalid logfile structure and automatic log creation (wihtout the install.sh)
* Define more weakspots for "Sick detection"
