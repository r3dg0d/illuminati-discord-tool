# illuminati-discord-tool
Codename Illuminati is the ultimate AI and ML tool for discord.

# To-Do (WIP)
- Code a discord bot template in python
- Code a voice-to-text model that decodes voices to text
- Implement the .wav files from the AI into the discord vc.
- Create a list of pre-determined results for certain responses. (i.e. basic calculations, weather regarding a location, etc.)
- Code a way to make discord bot join vc then record call for data
- Create .wav for bot to say in vc when it joins stating that the call is recording for data-collection for use with AI. 
- Add image based detection that detects Memes in discord, and responds with what it sees.
- Add multiple micro-bots (Codename: Illuminati) that run on Large-Scale Storage solutions and record discord calls permanently. 
- Make a virtual assistant from scratch, and make a command for it to join a vc.
- Use some NLP (Natural Language Processing) for processing requests that the bot doesn't understand.
- Code a textless text-to-speech model, that takes text from previous step, processes it, and creates a result. Natural Language Processing required. Look into blenderbot from facebook AI, and ParlAI's work.

# Notes
Codename: Illuminati needs storage for video recordings. Over the long-course of use, these recordings could use something called: Big Data. I'd recommend making a home data server, having a lot of storage, or using an NAS (network attached storage). These could be pretty pricey depending on how much storage is needed for the ML, and other code for the software. However once the software is pitched and sold to some big discord servers, it could come out to pay for operating costs.

Repl.it based on my knowledge doesn't allow npm to access the file system, so it is recommended to make an NAS to store all the data on for training.

For security and privacy purposes, cloud storage is not recommended. Local, Home based storage is recommended, or a peer-to-peer option like filecoin is possible. Even then, peer-to-peer has security flaws such as reverse-engineering hardware identifiers on the hard disk, or SSD, unless it is stored as a hash, which makes it harder to bruteforce.

# Resources

- Train an object detector: https://neptune.ai/blog/how-to-train-your-own-object-detector-using-tensorflow-object-detection-api
- Mozilla TTS: https://github.com/mozilla/TTS
- Play Discord Audio from URL: https://stackoverflow.com/questions/66115216/discord-py-play-audio-from-url
- Play Discord Audio from Local File: https://stackoverflow.com/questions/63036753/discord-py-bot-how-to-play-audio-from-local-files
- ParlAI library and documentation: https://ai.facebook.com/tools/parlai
- ParlAI Github: https://github.com/facebookresearch/ParlAI
- Blenderbot 2.0 Models: https://github.com/facebookresearch/ParlAI/blob/main/parlai/zoo/blenderbot2/model_card.md
