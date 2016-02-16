# coffeebot
Offer and order coffee.

## Setup

Register your bot on slack and take note of your bot token.

Create a .env file in your coffeebot directory with the following in it:

    SLACK_TOKEN=YOUR_BOT_TOKEN_GOES_HERE

Invite your bot to your channel with:

    /invite @coffeebot
    
## Starting a pot

Assuming you have 6 cups available, type the following in your channel:

    @coffeebot: 6 available
    
Coffeebot will start a pot and add you to the list.

## Getting in on that pot

Type the following in the channel:

    o/

When all the spots are full, Coffeebot will print out the list of everyone who's in on the current pot and reset.

## Resetting Coffeebot

Did you start a pot that nobody seems to want?  Type:

    @coffeebot: reset
