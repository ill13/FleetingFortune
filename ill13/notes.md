Please do a deep dive on this code. We have some features to discuss.

- Quest item needs to be purchased elsewhere and delivered to the requesting location. Player can't buy the fish at the wharf and redeem at the wharf. Also the items need to be "sold" at the destination to fulfill the quest
- When items are fully purchased and store stock depleted, don't remove the item from the inventory display. It's too confusing and the player is unaware that of what just happened. Just ghost it
- We need a current inventory on the trading screen.
- World map inventory not working either 



- In fact, only the top window should change between the trading and the world map
  


- Each location should only show what it is willing to buy and what it sells, always in the same vertical order





Better! Primary issue is that the marketInsights and back button are no longer visble unless we set the browser to use an extreme vertical length. I think the itemsList needs to be either limited to an amount that always allows for the visibility of those items or something like a fixed navbar on the bottom. Also, the inventory needs to scroll vertically.