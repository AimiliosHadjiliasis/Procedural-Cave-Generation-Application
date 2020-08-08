# Procedural-Cave-Generation-Application

***Project***
-----------------------
This is an application that generates procedurally caves with a GUI that is presenting 
the seed the width and the height of the map that is created. This application is a part of 
my research project on How Procedural Content Generation is used, for my Bachelors thesis project.

***Idea***
------------------------
The idea behind this project is to use a concept named Cecullar Automata and genetera an algorithm 
that will use the logic of cecullar automata to generate caves procedurally. Then we use the Marching Squares algorithm 
in order to generate small squares in the grid in based on the value that each point in the grid has (can be 0 or 1) we initialise
if that point is a wall or an empty field. After that we Create small paths that are connecting the Rooms that we created based on 
the cecullar automata algorithm and then we create the 3D mesh for the cave.

***The project until this point can be found here:***

Lastly, i created a GUI that uses that idea and is presenting the cave that is procedurally generated based on the seed that we passed 
as well as the width and height of the map.

***You can download the project from here:*** https://www.dropbox.com/s/7l4k14z2q4ionve/PCG%28x86%29.zip?dl=0

***Aknowledgment:***
------------------------
The main idea of the project was taken after finding a Guthub tutorial of AK-Saigyouji that explains the implementation of Procedural Cave Generation.
However, this tutorial was indirectly connected with Sebastian Leagues Series on Procedural Cave Generation so a part of the implementation of some algorithms like 
Cecullar automata, Merching squares etc have taken form him. Furthermore, in order to understand the implementation of Cecullar Automata 
algorithm i made a research on what is cecullar automata and how we can implement them codewise. All the links for the research on cecullar automata 
and the tutorials and series that i used can be found in the Main Sources section below after the Diagram of the Cecular automata and the screnshot of the GUI that is implemented. The explanation of the implementation of the project can be found in the link that is provided in the idea section above. 



***Cecular Automata Diagram that creates the Caves procedurally***
--------------------------------------------------------------------
![](/Images%20for%20Read%20Me/CecularAutomata.png)


***Application GUI:***
---------------------------------------------------------------------
![](Images%20for%20Read%20Me/GUI.PNG)





***Main Sources:*** 
**************************************************************************************************************************************
***CECULAR AUTOMATA:***

***Wikipedia:*** https://en.wikipedia.org/wiki/Cellular_automaton

***Standford Encyclopedia:*** https://plato.stanford.edu/entries/cellular-automata/

***Nature of Code:*** https://natureofcode.com/book/chapter-7-cellular-automata/

***Towards Data Science:*** https://towardsdatascience.com/algorithmic-beauty-an-introduction-to-cellular-automata-f53179b3cf8f

***Cellular Automata Machines: A New Environment for Modeling:*** https://books.google.com.cy/books?id=HBlJzrBKUTEC&pg=PA27&redir_esc=y#v=onepage&q&f=false
**************************************************************************************************************************************


**************************************************************************************************************************************
***YOUTUBE TUTORIALS:***

***Sebastian League - PCG Serries:*** https://www.youtube.com/watch?v=v7yyZZjF1z4&list=PLFt_AvWsXl0eZgMK_DT5_biRkWXftAOf9

***Daniel Hofmann - Auto generated Map Tutorial:*** https://www.youtube.com/watch?v=xNqqfABXTNQ

***The Code Train - Cecullar Automata Implementation:*** https://www.youtube.com/watch?v=DKGodqDs9sA
**************************************************************************************************************************************


**************************************************************************************************************************************
***Git-Hub Tutorials:***

***AK-Saigyouji on procedural Terrain Generation:*** https://github.com/AK-Saigyouji/Procedural-Cave-Generator

******AK-Saigyouji - Modules:*** *** https://github.com/AK-Saigyouji/Procedural-Cave-Generator/blob/master/Modules.md
**************************************************************************************************************************************

