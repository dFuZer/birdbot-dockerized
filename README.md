BirdBot, split into 4 dockerized services and orchestrated using docker-compose.
BirdBot is an autonomous bot that plays BombParty (the game) on JKLM.fun (the game platform). 
BirdBot enhances the experience of the players in BombParty.

4 services:
- the PostgreSQL Database
- the API (allows the Bot and the Website to interact with data from the database)
- The Bot (written in Rust for performance, interacts with the JKLM.fun platform, plays the game, manages the rooms)

To run:

1/ Copy the .env.example file into .env
2/ docker-compose up
