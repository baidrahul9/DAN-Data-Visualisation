# DAN-Data Visualisation
**Summary:**
<br>
This Data Visualization helps us analyze the goal-scoring ratio per game for football (soccer) players across the Spanish La Liga. It was desiged to show why Lionel Messi and Christiano Ronaldo are the best players in the world. 
<br>
<br>
**Design:**
<br>
The dataset being used in this project was collected via Wikipedia and it is a pretty straightforward dataset with 7 fields and 36 rows. I’ve collected for six different players from the years 2010 to 2015.  Since I’m new to the data visualization and javascript domain, I tried having the whole experience of collecting the data and try telling the story of goal scoring across seasons for the top football players in the Spanish league. 
I chose the Spanish league because they have witnessed the best footballers in the world and won the Ballon D'or every time since 2010, the year from the trophies' introduction. Since I wanted to show the players’ performance across the years, I chose line chart to display the trends in time. The feature that we are trying to compare is that of goals scored per season by the top goal scorers. The number of goals in a season is defined by the number of goals scored in that season to the total number of appearances in that season. Another feature we can used for comparision is the assists per season. These statistics help us understand why only Messi and Ronaldo have won the trophy since it's introduction in 2010.
<br>
I used Dimple.js and D3.js to create my visualizations. The first chart I came up is drawn below and this chart was created with the expectation that the user understands the idea behind the line chart being displayed. Below is the image of index_trial1.html, which shows the basic outlay of the chart.
<br>
![alt tag](https://github.com/baidrahul9/DAN-Data-Visualisation/blob/master/images/Initial.png)
<br>
<br>
**Feedback #1:**
<br>
Although the scatterplot dots show the name of the players, year and goals per game, it would be better to show the name of the player corresponding to the color of the line.
<br>
*Implementation:*
I added legend to the chart and made it more interactive and precise.
<br>
<br>
**Feedback #2:**
<br>
The chart seems pretty ‘bland’ and lacks interaction. It could be more animated and interactive to put forth the idea of comparison between players.
<br>
*Implementation:*
I added animation to the chart, which helps select 0-all players at a time for comparison and I also added more information in the tool-tip box that when a scatterplot is hovered on, it shows all the details from the data (csv) file.
<br>
<br>
**Feedback #3:**
<br>
The title doesn’t match and the interaction isn’t there.
<br>
<br>
**Feedback #4:**
<br>
The visualization isn't really explanatory yet.
<br>
*Implementation:*
Added a more story based approach to the project giving it a sense of direction.
<br>
<br>
**Conclusion from the Plot:**
<br>
Since this was my first D3 and Dimple project, I believe I have added enough interaction, kept the comparison open ended (more like the Martini glass concept). The users can now compare the players that they want and have better understanding of my story. The final output of index.html, looks like the image shown below:
<br>
Image without dynamic legend:
<br>
![alt tag](https://github.com/baidrahul9/DAN-Data-Visualisation/blob/master/images/Final_1.png)
<br>
Image with dynamic legend of two legends, Christiano Ronaldo and Lionel Messi:
<br>
![alt tag](https://github.com/baidrahul9/DAN-Data-Visualisation/blob/master/images/Final_2.png)
<br>
<br>
As we can see, it was always either Christiano or Lionel Messi that had the best goals per game ratio across all season but 2015-16 during which Luis Suarez scored more goals and had more assists than any other top player in the League. This can be attributed to the fact that Messi and Ronaldo play on the right and left forward positions whereas Suarez is out-an-out a striker. But, we should also keep in mind the consistency that Ronaldo and Messi have shown throughout the years while others have had careers with both highs and lows. This is what sets them apart! All the other players have been involved in the talks of Ballon d'or and have the best attacking statistics in the last 6 years but Messi and Ronaldo have won it all the time and I believe Christiano Ronaldo is going to win again in 2016 equalling Messi's tally of 3 trophies. With almost 1 goal per game and number of assists in double digits, we can clearly see who the 'champions' really are.
<br>
<br>
**Resources:**
<br>
1. Dimple.js
<br>2. D3.js
<br>3. Udacity Nanodegree
<br>
<br>
**Files:**
<br>
1. index.html
<br>2. Football_Data.csv
<br>3. index_trial1.html
<br>4. /images/

