# hey, what is vibrance?
Vibrance is a website that stores discord tags with their respective invites. This allows for anyone to effectively pick any tag they want and easily join the server they need to be able to use that tag.
# why did you make this?
Well, I first wanted to get some experience deploying a server on a VPS, and also I wanted a project I can show to people, and maybe those people can use it if they wanted.
# how will tags be recorded?
The VPS I mentioned will basically have a database that directly interacts with a discord bot. If the bot is invited to any server that has a tag, it will automatically store that tag in the database and also generate an invite for that server.
The webpage then interacts with the database too, with HTTP.
