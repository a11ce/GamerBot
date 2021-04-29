# GamerBot  

[GamerBot Twitch Bot](https://github.com/dilanx/gamerbot-twitch)

## About the bot
The main idea of GamerBot is to be able to talk to it using normal people sentences and receive varied responses rather than just running commands. You can say hi to it, and you'll receive a response back. You can ask it to remember stuff about you like your name, what you're favorite things are, etc., and then others (or you yourself) can ask it about you. You can even ask it math questions, questions about Northwestern courses or COVID-19 data, ask it what a word means, or even get some stock or crypto data. Have a song stuck in your head but don't know the name? You can share lyrics with it and it'll give you some songs that might match what you're thinking of. Oh, and weather data is there, too. It's very smart and can answer all of that without even needing to look it up unlike you (totally 100% legit not clickbait). [See a list of all the things the bot can do.](http://docs.blockhead7360.com/GamerBot)

## About the code
I've never made anything with Python before so I thought I'd learn it by making a Discord bot. All languages are close enough to each other conceptually so it was easy to figure out (I main Java). If you see a bunch of stuff in the code that could've been written more efficiently or that isn't standard Python convention, at least you know why now, but feel free to let me know because I'd love to learn.


## Changelog
See all of GamerBot's features here: http://docs.blockhead7360.com/changelogs/swwa-20010


## Contribution
Wanna add something yourself? Let me know and I can set you up. It's actually super easy to build your own stuff off of GamerBot's pretty abstract interface.

## External Data
If your curious about how the external data works, here's where the bot gets its information:

Dictionary and thesaurus data: [Merriam-Webster Dictionary API](https://dictionaryapi.com)  
Northwestern data: I just scrape it off their publicly-accessible [course](https://catalogs.northwestern.edu/undergraduate/courses-az/) and [COVID-19](https://www.northwestern.edu/coronavirus-covid-19-updates/university-status/dashboard/) websites lol  
Stock data: [Polygon.io API](https://polygon.io)  
Music data: [Genius API](https://docs.genius.com)  
Weather data: [OpenWeatherMap](https://openweathermap.org)
Minecraft username and UUID data: [Mojang API](https://api.mojang.com)
Minecraft avatar data: [Crafatar](https://crafatar.com)


## Privacy and Data Handling
I wanna work on some machine learning and AI stuff with this bc that sounds fun. So I should probably tell you that every time you send a message containing gamer bot's name in a channel it can access, it saves it to a file on my computer, noting your user id, channel id, and time as well :). This means if you sent a message to gamer bot but deleted it, I'd technically still be able to see it. If you don't want your messages to it saved let me know but like it's fine bro. Obviously all of the stuff you tell it to remember (your profile) is also saved because how else would it remember. Also if you're interested in how your save data looks (both message history and profile data), let me know and I can show it to you (I love talking about behind-the-scenes stuff lol). Also, it would be really cool if it could somewhat behave naturally like humans; for example, changing its mood depending on how people talk to it, and then forgetting about old feelings over time (hence the saving of messages and timestamps).


---

gamer bot is my child and forever will be

Started Feb 23, 2021
