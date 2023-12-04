# cmse202-project-group3
Semester project
Colonial War Modeling

Members:
Jonathan Le Roux
Ethan Hecht
Bhavya Jain
Pranav Agarwal

In order to run the code for our project all you need to do is shift enter on all the cells in the notebook titled War modelling.ipynb. There is nothing additional that needs to be done to execute the code properly.

In our project we decided to create a model that can be used to represent a colonial war between two countries. When creating this model we set out to answer the question of whether the number of soldiers a country has or the amount of money a country has is more important to the outcome of a war. In order to create this model we used different packages. Numpy, Pandas, Matplotlib, and NetworkX were used as tools to aid us in visualizing the results. In order to create our model we used two different classes, a country class and a territory class. The territory class is used in order to add soldiers to a territory and attack a territory from the other country. The country class is used to change the amount of money a country has, change what territories a country has, and add GDP after a certain amount of time has passed in terms of iterations. As each battle is fought we are able to visualize the war using NetworkX. We did this by making all the territories controlled by one country the same color node. Each node is connected to its nearest opposite colored node. Also, the nodes were connected by edges if they were less than twenty units apart from each other. By having an edge between the nodes it means that those territories are allowed to fight each other if they are colored oppositely. As for the attributes of the classes, the skill levels of the soldiers are dependent on the money a country has and the  number of soldiers is proportional to the population. Many iterations of the code were run in order to simulate the war many times in order to be able to fully see which factor has a greater impact on the probability of winning in a war. A number of different pairs of countries were initialized with varying initial GDP, population, number of soldiers and number of territories. Once this was done and the simulations were run, it was discovered that the most important factor was money per territory. The territory with the greater amount of money was the most likely to win in a battle based on the number of simulations run. Looking back at our method, the skill levels are directly related to the GDP of the country and since the war continues for a long time, the skill levels get much higher which makes them a very important factor.
	
In the project the work was divided among the group members. Pranav did the visualizations using NetworkX, Ethan did the country class, Jonathan did the territories class, and Bhavya created the simulations of the war. All group members worked together when creating the project slides and abstract.


