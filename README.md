# dotascience
SNA of transfers in dota 2

Interactive viz available at https://rpubs.com/vvseva/transfers_net_2 

In this project I have collected data from the https://liquipedia.net/

created several networks of transfers

and estimated them with ERGM (Exponential random graph models), that takes into modeling not only attributes (region, perticipation in top tournament, Elo rating, organization name), but structural effects too. 

For example Mutually increses probability of the transfer, and transitivity (GWESP) too.

Color is region, node size is degree
![Network](https://github.com/vvseva/dotascience-/blob/master/ic2s2transf.jpg)

China vs the world

In the China participation in The International (Top tournament) does not play role anymore, but there is another mobility path
(within the management organization) 
![table](https://github.com/vvseva/dotascience/blob/master/ERGM_table.jpg?raw=true)
