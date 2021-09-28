# illuminati-discord-tool
Codename Illuminati is a multipurpose discord bot used for AI, ML, and data-collection.

# To-Do (WIP)
✔️ Code a discord bot template in python.
✔️ Code a voice-to-text model that decodes voices to text.
- Implement the .wav files from the AI into the discord vc.
- Code a way to make discord bot join vc then record call for data
- Create .wav for bot to say in vc when it joins stating that the call is recording for data-collection for use with AI. 
- Add image based detection that detects Memes in discord, and responds with what it sees.
- Add nudity-detection algorithm
- Code a garbage collector that collects all messages in a specified channel and records it to a .CSV
- Add multiple micro-bots (Codename: Illuminati) that run on Large-Scale Storage solutions and record discord calls and video calls, with consent from the user(s).
- Make a virtual assistant from scratch, and make a command for it to join a vc. (Codename: SIVA)
- Use some NLP (Natural Language Processing) for processing requests that the bot doesn't understand.
- Code a way for the bot to record each discord message, and put it in a .csv file. Add start and stop command.

# Notes
Codename: Illuminati needs storage for video recordings, audio, text, and images. Over the long-course of use, these recordings could use something called: Big Data. I'd recommend making a home data server, having a lot of storage, or using an NAS (network attached storage). These could be pretty pricey depending on how much storage is needed for the ML, and other code for the software. However once the software is pitched and sold to some big discord servers, it could come out to pay for operating costs.

Repl.it based on my knowledge doesn't allow npm to access the file system, so it is recommended to make an NAS to store all the data on for training.

For security and privacy purposes, cloud storage is not recommended. Local, Home based storage is recommended, or a peer-to-peer option like filecoin is possible. Even then, peer-to-peer has security flaws such as reverse-engineering hardware identifiers on the hard disk, or SSD, unless it is stored as a hash, which makes it harder to bruteforce.

# Resources

- Train an object detector: https://neptune.ai/blog/how-to-train-your-own-object-detector-using-tensorflow-object-detection-api
- Mozilla TTS: https://github.com/mozilla/TTS
- Play Discord Audio from URL: https://stackoverflow.com/questions/66115216/discord-py-play-audio-from-url
- Play Discord Audio from Local File: https://stackoverflow.com/questions/63036753/discord-py-bot-how-to-play-audio-from-local-files
- Screen Record with openCV: https://www.tutorialexample.com/create-a-screen-recorder-using-python-opencv-opencv-tutorial/
- Collect Discord Messages: https://stackoverflow.com/questions/63322284/discord-js-get-an-array-of-all-messages-in-a-channel
- Record voice calls (WIP)
