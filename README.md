# Pass-Networks
Trying to make Pass networks more intuitive as well as rich in information. 

Pass Networks help us to analyze the main connections between different players during a match. By weighing pass importance in terms of distance or ball progression we can also find out the specific conections based on these conditions. A major drawback of such networks is the inability to paint this picture for the full match. We can only create a passmap before the first substitution occurs as after that the players on the pitch change. 

## Weighing Number of Passes

![](/images/Vanilla_network.png)

The following pass map tells us about the players which exchanged more number of passes among them during the course of the match along with their average positions. The importance of Sergio Busquets in the middle of the pitch with multiple strong connections all around tell us about the importance he exerted. The connections between Dani Alves and Messi as well as Jordi Alba and Neymar are evident as well. 

## Weighing Threat Created 

![](/images/xT_network.png)

Here the threat created by each connection is displayed. The size of the scatterpoints indicate the overall threat created by the player. The prominence of Neymar and Messi is highlighted with this. The threat created by a player is a good metric to evaluate creative midfielders as well as forwards, but the same should not be extended to defenders or defensive midfielders. Other metrics such as VAEP can be used to decide the size of the scatterpoints instead.

Suarez despite not being able to create a lot of 'threat' himself by his on the ball actions benefitted greatly from the passes he recieved from Neymar. 

## Waste of Possession?

![](/images/xT_waste_network.png)

By weighing the negative threat we can find out the connection which was not fruitful in creating chances. Suarez as shown in the previous network didnt create much of threat, most of his passes to Messi were as such 'negative' in nature. 
