# Battlefield-honor
A Battle royale game for the real ones. Built with Phaser 3, ReactJS and Colyseus, Battle arena - battefield honor is a survival game in its epiphany which brings players in unkown locations of a map together and force them to fight for thier survival. It came form the concept of popular games such as [Fortnite](https://fr.wikipedia.org/wiki/Fortnite) or [Pubg](https://fr.wikipedia.org/wiki/PlayerUnknown%27s_Battlegrounds) 

## Technical information
* Our game's frontend is developed in [PhaserJS](https://phaser.io/) - a js framework which gives us the possibility to build HTML5 games with less stress. We use [ReactJS](https://en.reactjs.org) for the game ui. We ensure a consistent state management through our game app with [Redux](https://redux.js.org/) and a good url management with [React router](https://reacttraining.com/react-router/web/guides/quick-start)
* Our game's backend is done with nodeJS which uses [Colyseus](https://colyseus.io/) to implement a powerful multiplayer game server.
* The sound, image assets from the game are all from various internet sources (All Open Source)
* The map of the game has been drawn using Tiled Map Editor - a powerful tool to draw game maps.

## What we have already implemented
* The display of the map on the game.
* The mouvement of the player and its rotation according to the position of the mouse even while moving.
* The connection between the client and the server which permits us to:
  * Send message between players to see, who is dead, who just entered the party, who left it etc
  * The server to send updates about some crucial information such as other players position in the map
* The firing of the bullet by the player and its collision with other player to eliminate them.
* The score which shows how many players has been eliminated by a particular player.|
* SoundTrack when the playing in the game.
* Sound effects for the game (bullet firing).
* HUD's to display the useful information about the player such as its health.

## What we still have to implement
* Multiple rooms to host multiple parties and add limitations to number of player allowed per room.
* A Menu system to help the player navigate along the game.
* Powerups and special abilities that the player can have along the game.
* More weapons of course!!!
* Authentication for persistent players and those who wnat to keep thier gained XP's and rewards. (primarily with facebook)
* intergration with facebook instant games(optional).
* push notification systems and data storage implemented with firebase for players to be able to save thier highest scores, XP's and rewards.

## How to install it
To be able to install and run the game, you need to download:
* [Git](https://git-scm.com/downloads)
* [Node](https://nodejs.org/en/) - take the LTS (latest stable version) version

After installation of the above programs, if you didm't have them...

1. clone the repository by entering the command below in your terminal.

  ```git clone https://github.com/ArnolFokam/Battlefield-honor.git```

2. Navigate to the folder of the project using your terminal 

3. Next, enter this command in your terminal to install the dependencies you need for the game.
  ```npm install```
4. Next, enter this command in your terminal to build the frontend files you need for your game to run on your browser.
  ```npm run build```
5. Then run this command to run the game server on your computer.
  ```npm run start:server```
6. That's it. Your server is up and running. By now, you can open a couple of pages to test it on you computer.
  * [http://localhost:2567](http://localhost:2567) can be opened in you browser to see and play the game.
  * [http://localhost:2567/colyseus](http://localhost:2567/colyseus) can be opened to monitor the  status of your game server. (client connected, rooms etc)

Note: if you want others to access the webpage and play the game. You must be connected through the same network and they must replace the localhost in the url with your IP address in the network.

To know your IP address in the network. this link may help you. :point_right: [Find your computer's IP address](https://kb.iu.edu/d/aapa)  
Search for the IP address with the form 192.168.X.X

## Who is behind this
Three brightful minds namely:

 [Arnol Fokam](https://github.com/ArnolFokam/) - JS Ninja and cold blooded Game architect.  
 [Teddy Baha](https://github.com/Wil2129) - Firebase Samurai and Ace critical thinker.  
 [Alex Jordan](https://github.com/alexjordan05) - Graphics Sensei and Gamer in the Soul.  

## Credits
 * The player in the game was inspired by the players in [surviv.io](http://surviv.io) and the player's sprite was obtained from this [website](https://survivio.fandom.com/wiki/Creator_Kit).
 * The assets we used to do the tilemaps was obtained from [Kenny's website](https://www.kenney.nl/assets/topdown-shooter).

## Useful ressources
 * [Phaser 3 Examples](http://labs.phaser.io)
 * [Phaser 3 API Documentation](https://photonstorm.github.io/phaser3-docs/)
 * [Colyseus 0.10.x docs](https://docs.colyseus.io)
 * [Github colyseus/colyseus-examples](https://github.com/colyseus/colyseus-examples)
 * [Create a Multiplayer Pirate Shooter Game: In Your Browser](https://code.tutsplus.com/tutorials/create-a-multiplayer-pirate-shooter-game-in-your-browser--cms-23311)
 * [Simple Redux Create Delete Contact Application](https://www.codingame.com/playgrounds/9169/simple-redux-create-delete-contact-application)

