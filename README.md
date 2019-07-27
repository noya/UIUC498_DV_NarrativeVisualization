# UIUC 498_Data Visualization #
## World Suicide Rate ##

*Cindy Tseng (cindyst2@illinois.edu)*


**Messaging. What is the message you are trying to communicate with the narrative visualization?**

  * In this project I'm trying to protray the suicide rate associated with different attributes around the world.


**Narrative Structure. Which structure was your narrative visualization designed to follow (martini glass, interactive slide show or drop-down story)? How does your narrative visualization follow that structure? (All of these structures can include the opportunity to "drill-down" and explore. The difference is where that opportunity happens in the structure.)**

  * I'm using an interactive slide show structure to help the user navigate.
   The whole story is presented in 3 charts, each chart has tooltips to allow the user to interact with the slideshow. 


**Visual Structure. What visual structure is used for each scene? How does it ensure the viewer can understand the data and navigate the scene? How does it highlight to urge the viewer to focus on the important parts of the data in each scene? How does it help the viewer transition to other scenes, to understand how the data connects to the data in other scenes?**

   * Each top center of the scene shows the title of the graph. This is so that the user can quickly grasp what the topic of the scene is about. 

   On the left part of the scene is a text panel providing more elaborate highlight. 

   On the right part of the scene is the actual chart displaying the data. The chart takes up the largest area of the screen to grab the user's attention.

   Each scene uses the same template so the user can quickly orient themselves and connect the scenes. It toggles the current page number to indicate which part of the story the user is on. 


**Scenes. What are the scenes of your narrative visualization? How are the scenes ordered, and why**

   * Each scene is a graph with y axis displaying the average suicide rate and the x axis displaying the year from 1985 to 2016.
   
   The overview scene is put in the first page. It lists the overall suicide rate along with different major events happening in the world. This is so that user can immediately get the big picture. Later scenes examines the suicide rate with other dimension such as sex and age.


**Annotations. What template was followed for the annotations, and why that template? How are the annotations used to support the messaging? Do the annotations change within a single scene, and if so, how and why**

   * The annotations has 3 components: note, subject, and connector. Note contains text that highlights the event; Subject points out the location of the event on the graph; Connector connects the note and the subject together. This template helps the user understand the highlight point, and the event associated with highlight. 

   The annotations again help support messaging by pointing out the highlighted event and providing text to highlight the event. 

   The annotations remain the same within a single scene. However they do appear few seconds later than the chart to help user notice them.


**Parameters. What are the parameters of the narrative visualization? What are the states of the narrative visualization? How are the parameters used to define the state and each scene?**

   * The parameters are the page numbers and each page number are linked to a unique state. When the user clicks on the page buttons, the current page number changes and thus the state changes and the scene is updated. 


**Triggers. What are the triggers that connect user actions to changes of state in the narrative visualization? What affordances are provided to the user to communicate to them what options are available to them in the narrative visualization?**

   * The triggers are the act of clicking the page buttons. Affordance is provided by darkening the buttons when the users hover their mouse over them. The buttons stay dark if the user actually clicked the buttons indicated the current page is selected. 

