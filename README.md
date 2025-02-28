BirdBot, split into 3 dockerized services and orchestrated using docker-compose.
BirdBot is an autonomous bot that plays BombParty (the game) on JKLM.fun (the game platform). 
BirdBot enhances the performances of the players in BombParty.

4 services:
- the PostgreSQL Database
- the Website (written in Next.JS, serves as a landing page + lists the records)
- the API (allows the Bot and the Website to interact with data from the database)
- The Bot (written in Rust for performance, interacts with the JKLM.fun platform, plays the game, manages the rooms)