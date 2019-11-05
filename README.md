# 4602-Mozilla
# Group 5:

<li>Jiahao Wang (jiwa8909@colorado.edu)</li>
<li>Juliet Anne Mcfarlane (Juliet.Mcfarlane@colorado.edu)</li>
<li>Jiaheng Zhao (jizh3194@colorado.edu)</li>

<h2>Team Member Roles: </h2>
<li>Jiaheng Zhao: First Visualization.</li>
<li>Jiahao Wang: Second Visualization.</li>
<li>Juliet Anne McFarlane: Analyze the data.</li>

<h2>Design Process:</h2> 
Brainstorming: The first step in the process is to come up with a visual idea. We got together as a group and exchanged thoughts on the survey questions and how they could be correlated. After analyzing the complex data, we decided to implement two visualizations. We wanted to focus on privacy because it is becoming a huge issue in today’s society. Just as our idea meets the requirements, a visualization that includes quantitative data and a visualization that includes categorical data. 

  

<h2>The first visualization:</h2> 
we will analyze the following columns - "Privacy: You are planning on buying your next cool new tech toy. Maybe its a smart TV or a new smartphone. Take a look at the items below and Include them in order of importance as you make that purchase." We intend to use the world map to express the degree of privacy of people in different countries with the brightness of the colors. 


<h2>The second visualization:</h2> 
We will then use the pie chart to analyze the following problems: "What is your biggest fear as we move toward a more connected future?" This will be interactive as you click on different countries. Viewers can see the proportion of people in each country with different answers to this question.

<h2>Preprocessing:</h2> 
Use python to preprocess the raw data and count the answers to these two questions for each country. After filtering out the null values, we calculate the average value of the problem — “Privacy:You are planning on buying your next cool new tech toy. Maybe its a smart TV or a new smartphone. Take a look at the items below and arrange them in order of importance as you make that purchase”, which corresponds to the color of the map. Using python to calculate the number of different opinions, in the following question - "What is your biggest fear as we move towards a more connected future?" The number of people in different opinions corresponds to the size of the pie chart.

<h2>Interactivity:</h2> 
Both visualizations contain information revolving around privacy. The first visualization is a ranking scale of the importance of privacy. It correlates with the second visualization, which gives more details on the fear of the respondents from each given country. By clicking on a country from the first visualization, the second visualization will pop up. This allows you to directly correlate the information on privacy and it’s importance because both of the survey questions gave answers related to privacy.

<h2>Insights:</h2>
Our first visualization involves a map. We focused both visualizations on the importance of privacy. The first visualization revolves around the question "You are planning on buying your next cool tech toy. Maybe it's a smart TV or a new smartphone. Take a look at the items below and arrange." The options listed for the respondents were “price,” “features,” “safety,” “security,” “privacy,” “reliability,” “user reviews,” “expert reviews,” “friend or family recommendation,” and “convenience.” The darker a country is, the more that they value privacy as the most important. If we take a look at Algeria, we can see that it is the middle brown shade. That means that the average of the ranking of privacy for respondents in Algeria was between 4-6. By looking at the visualization, we can see that most countries value privacy pretty heavily, as most countries are the middle shade to the darkest shade. The visualization takes the average of the rankings for the privacy of the respondents based on their countries. This gives us an idea on how much they value privacy when they are looking into trying out a new technology. 
The second visualization is a pie chart. We focused on the question: "What is your biggest fear as we move towards a more connected future?" This is interactive, so as you click on a country, you can gain some insight into the country’s thoughts on this question with a pie chart. The five options for answers were “the loss of privacy,” “we'll be less safe,” “we'll lose touch with one another,” “I have no fears about a more connected future,” and “other (please specify).” For example, as we can see on the country Algeria, the loss of privacy was the most answered, followed by we'll lose touch with one another, we'll be less safe, and I have no fears about a more connected future. The goal of our visualizations were to focus on what fears countries have as we move into the future of a very technology based world and how a lot of those fears involve privacy. This is important as technology quickly evolves. This visualization could be very useful to Mozilla because companies need to know the importance of privacy for the future. As you can see by just looking at the map, most countries fall in a range that involves privacy. Then, as you click on countries, you can dig deeper into their fears. Just as most countries gave privacy a ranking of 4 or more, there were similar results in the second visualization. The loss of privacy was answered as the majority for many countries. This really says something considering that a huge majority of respondents considered themselves to be ultra nerds, technically savvy, or an average user. Those respondents are likely using their devices a lot, which means they have a lot to consider when it comes to the future. 


<h2>Accomplishment:</h2>

(1) Minimum Requirements:
<ul>
<li>One visualization includes some quantitative data.</li>
<li>One visualization includes categorical data.</li>
<li>Each visualization be interactive.</li>
<li>Our visualizations support at least one meaningful comparison between related data attributes.</li>
<li>Our visualizations visualize at least five data attributes total.</li>
</ul>

(2) Above and Beyond:
<ul>
<li>Unusual Representations: Draw on some of the examples from class to represent data in ways beyond a typical scatter plots or bar chart.</li>
<li>Geography: Incorporate maps or other geospatial data components into your visualization.</li>
<li>Coordinated Views: Have two or more visualizations that interact with one another as you move through the data.</li>
</ul>

<h2>Build Instructions:</h2>

<ul>
<li>(1)Launch a server in the root directory(named as “visualizations” folder): python3 -m http.server 8000</li>
	
<li>(2)http://localhost:8000/index.html</li>
</ul>
	
