# bid-bot
A algorithmic trading bot which bids on players on http://hitwicket.com/


### Introduction

* The website is a cricket management game.
* Cricket players (virtual) are auctioned realtime on the website.

## Constraints

* Players have attributes which indicate their skills, age and few other things.
* Bids may be placed for a 48 hour or a 72 hour interval.
* There is a minumum selling price set for each player.
* Agent fees is a big constraint. Can be thought as brokerage fees.
    1. Less than 10 days - 35% agent fee
    2. 10-19 days - 25% agent fee
    3. 20-29 days - 15% agent fee
    4. 30 days or more - 5% agent fee
* Placing a bid cost the exact same amount,
* For selling a market cost of 5000 is placed, regardless of whether player is sold or unsold
* Start off with a fixed but decent capital.


### Aim

* Scrape data off the website
* Make a trading bot to do this
* Predict the selling price of the player
* Place bid if a profit can be made
* Not get banned on this site



*Note - Doing this purely as a learning project*

