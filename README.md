# illuminati-discord-tool
Codename Illuminati is a Discord AI that detects nudity in discord video calls, and chat, and bans users if found.
Kinda like Apple's new tool they are implementing on iPhones, using hashes, but instead of hashes, we are using a custom algorithm that detects nudity from a database of images. Eventually want to be able to detect it in video calls, using frame-by-frame analysis, or another, less storage-intensive method.

Lets provide a safer space for people to chat. #ProjectIlluminati on twitter.

#To-Do
- Code a discord bot template in python
- Code a way to make discord bot join vc then record call
- Code algorithm, if it detects nudity, Ban user instantly.
- Create .wav for bot to say in vc when it joins stating that the call is recording for any rule-breakers. 
- add image based detection that detects harmful material in discord channels.
- Add multiple micro-bots (Codename: Illuminati) that run on VPS and record discord calls permanently. They respond to toxic words, nudity, and other TOS-related things in its own manner.

# Notes
Codename: Illuminati needs storage for video recordings. Over the long-course of use, these recordings could use something called: Big Data. I'd recommend making a home data server, having a lot of storage, or using an NAS (network attached storage). These could be pretty pricey depending on how much storage is needed for the ML, and other code for the software. However once the software is pitched and sold to some big discord servers, it could come out to pay for operating costs.

Repl.it based on my knowledge doesn't allow npm to access the file system, so it is recommended to make an NAS to store all the data on for training.

For security and privacy purposes, cloud storage is not recommended. Local, Home based storage is recommended, or a peer-to-peer option like filecoin is possible. Even then, peer-to-peer has security flaws such as reverse-engineering hardware identifiers on the hard disk, or SSD, unless it is stored as a hash, which makes it harder to bruteforce.
