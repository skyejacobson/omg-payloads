# The purpose of this payload is to locate, copy, and exfil all iMessage data for in-depth reconnaissance, including the following:

# (1) All messages sent since first boot of laptop.
# (2) Emails, phone numbers, UIEDs to identify where the message came from/was going to
# (3) Any other information stored in the chat.db file

# Prequisities required for this payload to work (efficiently):

# (1) You need a working email (I chose email because DropBox is too unreliable to be used in MacOS Ventura)
# (2) This has so far only been tested on MacOS Ventura and Monterey so victim's machine should look to be updated however if it works on newer OS versions it should work on older ones.
# (3) Please understand this specific code has been modeled a little more around a newer M1 machine so if you plan on testing on older (slower) machines, I'd reccomend doing a little adjusting to the timing of the payload and the exploits within.


