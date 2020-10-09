# PaloAlto_FoldingAtHome
How to get Folding at Home working with a strict Palo Alto NGFW ruleset

I had some trouble getting Folding At Home working through my Palo Alto PA-220. I couldn't find any published information on exact ports, IP addresses, or URLs to allow. After some research and digging through logs, I finally ended up with a nice, strict ruleset that only allows the necessary traffic. For reference, this site lists the active servers -https://apps.foldingathome.org/serverstats. So I used that and cross referenced traffic logs to get the necessary App-IDs and ports.

So for those of you that want to get FAH working through your Palo Alto firewalls, here is how I did it. I included a set_commands file that gives you all the necessary set commands to match my configuration. I also included a custom URL category with all of the currently active servers for those of you that wish to filter by URL instead of IP address.
