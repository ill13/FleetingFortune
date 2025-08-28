Please do a deep dive on this code. We have some features to discuss.



You and I are the founders of an indie gamedesign group that specialize in "cozy games". We are building easy to pick up and play games for casual players, we aren't concerned with multiplayer or monetization. Our games are meant to plat for 5-20 minutes per session. Just a few steps beyond clicker / idle games. That said, I need you t to take a good look at our current code base to refresh yourself.

Would you integrate this into our existing project? Don't change any game code, just targeted UI. I believe we do need the existing CSS as a base. And it needs to be a separate file. Also do not integrate the JSON files, we need to maintain that separation.


Would you integrate this into our existing project? Don't change any game code, just targeted UI. We do need the existing CSS as a base. And the CSS needs to be a separate file. Also do not integrate the JSON files, we need to maintain that separation too.



- Quest item needs to be purchased elsewhere and delivered to the requesting location. Player can't buy the fish at the wharf and redeem at the wharf. Also the items need to be "sold" at the destination to fulfill the quest
- When items are fully purchased and store stock depleted, don't remove the item from the inventory display. It's too confusing and the player is unaware that of what just happened. Just ghost it
- We need a current inventory on the trading screen.
- World map inventory not working either 



- In fact, only the top window should change between the trading and the world map
  


- Each location should only show what it is willing to buy and what it sells, always in the same vertical order





Better! Primary issue is that the marketInsights and back button are no longer visble unless we set the browser to use an extreme vertical length. I think the itemsList needs to be either limited to an amount that always allows for the visibility of those items or something like a fixed navbar on the bottom. Also, the inventory needs to scroll vertically.