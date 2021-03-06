# CS 498 Data Visualization Final Project 
Summer 2020

Pui Sze Pansy Ng (netID: ppn2)

website: https://pansyng.github.io/498-final-project/index.html

# Introduction 
In this project, I use the data provided by Dr. Kristen Gorman and the Palmer Station, Anatarctica LTER, a member of the Long Term Ecological Research Network. The dataset contains data of 342 penguins. There are 3 different species of penguins in this dataset. They are collected from three different islands in the Palmer Archiplago, Antarctica.

# Messaging 
With this narrative visualization, I am trying to show the relationship between the flipper length and body mass of penguins from three different islands in Antarctica. 

# Narrative Structure 
I have used interactive slide to show the narrative visualization. In the Scatterplot page, there are three tabs below the title and each tab represents a scene for viewer to explore every step of the story. After that, I also create an extra page that summarizes the data set with genders of penguins and islands where penguins are collected from. 

# Visual Structure
For visual structure, I have used a stepper model for the scatterplot which will display each scene with descriptions after clicking the scene button. I also used the mouseover feature which can highlight different set of data with different colors and can change caption after clicking on each scene. These captions will guide the viewer to locate types of penguins. Viewer finds the species of penguins by checking colors indicated in the legend of the chart. Besides, there is one scene with stacked bar chart plot. That scene is used tooltip to the dataset of the each section of bar. 

# Scenes 
There are five scenes in total: four scenes inside the scatterplot with scenes button and one scene with the stacked bar chart plot by clicking "here" at the bottom of the scene page. For the scatterplot, it shows automatically the first scene and it allows viewer to move curser to the data with coloered highlight for each type of penguins. The second scene is required to click the "Scene 2" button which is located next to "Scene 1" button and below the graph title. After clicked Scene 2, it shows "Adeline and Chinastrap have very similar flipper length and body mass" and implicitly to guide the viewer to locate Adeline and Chinastrap's data. For Scene 3, the button is located next to Scene 2, it guides the viewer to look for the Gentoo's dataset. For the finally scene in the scatterplot, it reveals a positive correlation between the flipper length and body mass. At the bottom of each scene page, it will direct the user to the next page which is the stacked bar chart page (scene 5). 
For the stacked bar chart page, it contains two stacked bar graphs. The left side graph summarizes the gender of penguins. The dataset contains three types of gender: male, female, and na. The right side graph summerizes the islands where the penguins are located. Penguins come from three different islands: Biscoe, Dream, and Torgersen island. For both dataset, I have used a stacked bar chart to the data. 

# Annotations
Starting from the homepage, I have maintained to use the same design for each page. For this assignment, I have created three pages. These three pages contain header with same font and color. The home page contains an essay which has consistent fonts and format. The scatterplot page which is used stepper model to contain the same font. After clicking the next scene, viewer will find the caption of the last scene disapears and display the next caption for that scene. Each scene will invite viewer to explore different set of data. The stacked bar chart page containing two graphs are used the same format and design. When the cursor moves to specific section of the bar, it will show the data of that section with summary. 

# Parameters 
The parameter used in this visualizaton is the categorical variable "species" and the current state of the parameter is "species". Viewer has the ability to investigate one type of penguins one at a time by moving the cursor on the data belonging to that particular species of penguins and the current state will change to that specific species. This allows the user to gain more information about the relationship between flipper length and body mass, not only as overall trend, but also based on the species type as well. On the second page also used the mouseover to indicate that specific species of penguins.


# Triggers 
Triggers are used in two ways for this visualization. 
First, trigger is set by clicking the button of each scene. For the scatterplot, the buttons on the top of the visualization containing affordance to guide the viewer which action is available. The button are labelled "Scene 1", "Scene 2", "Scene 3", and "Scene 4". By clicking each button, the current state of the visualization will be changed and different annotations will pop up.
Second, a trigger is set by pointing to the data.  Mouseover to each data point will show colored highlight for species of the penguins from scene 1 to scene 4 and detail of the stacked bar chart on scene 5. 



# References
- Dataset for Palmer Penguins
> Horst AM, Hill AP, Gorman KB (2020). palmerpenguins: Palmer Archipelago (Antarctica) 
> penguin data. R package version 0.1.0. 
> https://allisonhorst.github.io/palmerpenguins/. doi: 10.5281/zenodo.3960218.
- Example for Scatterplot and stacked bar plot: https://www.d3-graph-gallery.com/index.html
- Tutorial for building a stepper page: http://vallandingham.me/stepper_steps.html



