> Project Name: Build Data Dashboards <br>
> Data Source: [Youtube US Data](https://www.kaggle.com/datasnaek/youtube-new/data) <br>
> Description: This project aims to provide insignts in forms of visualization about the original dataset, recording information of the US Youtube Videos that were trending for at least one day from 17 November 2017 to 17 March 2018.<br>

> *Note: the dataset used to create the visualization was cleaned in Excel previously:*<br>
> + *The orginal trending data in forms of "YY.DD.MM" was transformed into "YYYY-MM-DD";*<br>
> + *The "total" value here was the maximum value selected from the original dataset. E.g.Total views = Max.Views recorded on the dataset since the dataset recorded the accumulated data.*
### Question 1: Do types and hot tags of Youtube Top trending video differentiate between states?
#### Tableau Link: [Youtube US Viewers' Favorites](https://public.tableau.com/profile/wangyun.wu#!/vizhome/YoutubeDataAnalysis_15941863358400/DashboardbyGeographicalSituation?publish=yes)
#### Summary
&emsp;This dashboard collects the basic data of Youtube top trending video (listed from 17 November 2017 to 17 March 2018) geographically. It displays channel category, hot tags, the number of channels, total views, total likes, and total dislikes, as well as the count of total comments for each state. The color of the state represents the number of the views.<br>
&emsp;It is reasonable to conclude that the situation from state to state. For example, California, which gains the most views, has 224 different channels in total, most of which are under entertainment or music category. The hottest tag is “humor”; for Pennsylvania, which owns 28 channels, has hot tags focusing on an American actress “Koshy”.<br>
#### Design
&emsp;The first visualization I created is the map section, which is also the start of my exploration. After including some basic data (number of views, likes, and dislikes), I first want to cite the channel title that gains the most views in each state, but I soon find that I will lose the advantage of visualization. However, I find the variety of categories so attractive for me. I simply choose to plot different channels in each state according to their category. This section delivers information concisely by distinct colors and the number of objects. I also add the data such as views and likes to enrich the visualization. At the same time, the tag – one of the special characteristics of Youtube – is worthy to be explored. I used a heatmap to quote hottest tags, the size and the color of which could show the degree of their popularity.<br>
#### Resources
&emsp; N/A <br>

### Question 2: What are characteristics for Top 10 Youtube Viewer Winner Channel?
#### Tableau Link: [Top10 Youtube Channel](https://public.tableau.com/profile/wangyun.wu#!/vizhome/YoutubeDataAnalysis_15941863358400/Top10YoutubeChannel)
#### Summary
&emsp;This dashboard displays detailed information for the top 10 Youtube Viewer Winner channels, ranked by the total number of views for all videos in the same channel. It collects tags, trending views over time, views for each video, and the proportions of “key metrics” (average views, likes, views, comment count). The detailed information of the specific video will be displayed if chosen.<br>
&emsp;Most channels on the list are music channels with tags of the musician’s name such as Taylor Swift VEVO and ibighit. They can always hit the hot spot when a new song’s MV is launched. A trending video may lead to the growth of views of related videos, such as Marvel Entertainment.
#### Design
&emsp;The first visualization I created is the trending views over time section. Since the sample size is too large to deliver the information, I chose the 10 most viewed videos as a filter. The line chart could express the trending very clearly. I choose a bubble chart to cite the tags, the size of which represent the count. The bar chart of views shows the views of each video separately. The audience will distinguish the most viewed or liked videos directly. They can also get a zoom trending views for the selected video by clicking the bar. The pie chart displays the proportions of the key metrics. 
#### Resources
&emsp;N/A

### Question 3: What are characteristics for videos with a considerable number of views.
#### Tableau Link: [Views Exploration](https://public.tableau.com/profile/wangyun.wu#!/vizhome/YoutubeDataAnalysis_15941863358400/Big-numberviewsExploration)
#### Summary:
&emsp;This dashboard displays detailed three sperate scatterplots and a conclusion plot. It shows the three factors – number of tags, total trending days, and category – potentially related with the large number of views. The target view could be selected beside the title.<br>
&emsp;No evidence could show the number of tags is a key factor to influence the number views. For videos with large number of views (e.g. 20,000,000), most of them have been trending for more than five days. Most of them belongs to the music category.
#### Design
&emsp;I use three scatterplots to display the relationship between the selected factor and the number of views. To conclude the result more concisely, I use a syntax scatterplot, the y-axis showing the total trending days, the color representing the category, and the size of plot displaying the count of tags
#### Resources
&emsp;N/A

