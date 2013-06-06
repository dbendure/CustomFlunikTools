CustomFlunikTools
=================
1) It chooses to upgrade Off RT buildings based on highest time greater than 4hours before it can do resource buildings.

2) Building set is trying to push CY, CC, DefHQ 3 levels higher than the base. "DefFac needs taloired to plus three of the DefHQ"

3) Upgrades Support buildings, and DefFac if can.

4) Chooses to Upgrade the highest production ratioed building.(upgraded past level doesn't have power cost, then upgrades base on:
((currentprodution+currentconnectedlinktypes)/(currentpowercost))/((level12prodution + one of each possible linktype)/(powercostoflevel12))

5) Def and Off units just upgrade if possible."May need to be taliored to hitpoints over cost"Fixed!

6) Above all it upgrades one unit and/or (building or building set) per loop. by doing this I'm able to set the time it loops much faster than one minute. I have it looping every 10 seconds.
