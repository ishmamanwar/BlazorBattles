# Blazor Battles Game Project by EVOLVE Projects (Ishmam Anwar)

## Tech Used

 - ASP.NET Core 3.1
 - Blazor
 - Postman
 - SQLite DB

## Features

 - RESTful API
 - Follows MVC architecture
 - Register/Login with JWT functionality
 - Dynamic Nav Bar based on level of authorization
 - Can view "Build", "Army", "Leaderboard" and "Battle History" pages only if logged in.
 - All data are saved in the SQlite db
 - Necessary Validations are done on the client and the server side
 - Error and Success messages are provided with Toast Services


## Demo
 - https://github.com/ishmamanwar/BlazorBattles-blazor-.net-core/blob/master/Blazor%20Battles%20Trim.mp4 (Click View Raw)

## App Overview

 - Register for an account/ Login to your account
 - Build an army of Knights, Archers and Mages using allotted "Bananas" (Selected resource for the game)
 - Each unit has a unique Attack Number, Defense Number, HP and Banana Cost
 - View your built army on the "Army" Page to see their current HP and other details once you're logged in
 - View the other registered players on the server at the "Leaderboards" page which displays total battles fought, wins, losses and button to fight the said player
 - Once entered battle each unit of the logged in player attacks a random unit from the challenged player's army and vice versa
 - If all units of a given player has 0 HP, the battle is conculded and a battle log pops up with the details of the fight
 - The battle history is saved on the "Battle History" page
 - The winning player earns banana equal to the damage caused to them by their opponent and the losing player earns banana ten times the damage caused by their opponent (funny mechanic for testing!)
 - Players can resurrect their army on the "Army" page for 1000 bananas. The units get resurrected with random Hit Points ranging from 1 to 100.
 - Have fun and climb the leaderboard!!


## Other Details
 - All of the API methods are tested with Postman
 - The database was double checked with each interaction

*
cd BlazorBattles
cd Server
dotnet watch run
*


