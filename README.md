# Lua-Project-Tycoon


-Description: 
One of my older but most completed project using lua. Much of the game was coded by myself, aside from a few other assets created by other team helpers. This game was a "Tycoon" game where the goal was to make money and "upgrade" your buisness to unlock everything. The result of this project was instantly shown with a massive success rate in obtaining over 1 millions plays and 100 concurrent players at its peak in a 3 month span. Game analytics was used to tweak certain aspects of the game to improve playability which resulted in an exponontial-like growth of game popularity.

- Random Crate Drop System:
Coded a randomized crate drop system where an object (crates in this instance) would be placed in random locations through out a map. If a user touches it then it would give that user a random amount of money. Used functions, storage, and a few variables to complete this in a more effecient way.

- MarketPlace GUI and System
Created a purchase GUI where there would be many clickable buttons, all being able to purchase different amounts of in-game currency. The system was created in a relatively easier way of code by using the "Marketplace Services", which is part of the API exlusive to the Engine.

- Dropper System
In order to make money in game there are "droppers" that drop items into a conveyer and fall in to a bin to make money. While this system is nice to have and very popular there are a few keys issues, multiply the amount of dropped items with 7 users and there are going to be alot of running scripts related to droppers alone in game. This would cause alot of lag, to help aleviate this issue, drops would only be temporary if the dropped item would get stuck in any way. This system used Storage and one variable with many different properties.
