# DAN-Data Visualisation
**Summary:**
<br>
This Data Visualization helps us analyze the goal-scoring ratio per game for football (soccer) players across the Spanish La Liga. 
<br>
<br>
**Design:**
<br>
The dataset being used in this project was collected via Wikipedia and it is a pretty straightforward dataset with 5 fields and 36 rows. I’ve collected for six different players from the years 2010 to 2015.  Since I’m new to the data visualization and javascript domain, I tried having the whole experience of collecting the data and try telling the story of goal scoring across seasons for the top football players in the Spanish league.
Since I wanted to show the players’ performance across the years, I chose line chart to display the trends in time. The feature that we are trying to compare is that of goals scored per season by the top goal scorers. The number of goals in a season is defined by the number of goals scored in that season to the total number of appearances in that season.
I used Dimple.js and D3.js to create my visualizations. The first chart I came up is drawn below and this chart was created with the expectation that the user understands the idea behind the line chart being displayed. Below is the image of index_trial1.html, which shows the basic outlay of the chart.
<br>
![alt tag](http://url/to/img.png)
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
**Conclusion:**
<br>
Since this was my first D3 and Dimple project, I believe I have added enough interaction, kept the comparison open ended (more like the Martini glass concept). The users can now compare the players that they want and have better understanding of my story. The final output of index.html, looks like the image shown below:
<br>
Image without dynamic legend:
<br>
![alt tag](http://url/to/img.png)
<br>
Image with dynamic legend of two legends, Christiano Ronaldo and Lionel Messi:
<br>
![alt tag](http://url/to/img.png)
</br>

