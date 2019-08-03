# UIUC 498_Data Visualization #
## World Suicide Rate ##

*Cindy Tseng (cindyst2@illinois.edu)*

The dataset used for this project is taken from Kaggle [https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016]

**Messaging. What is the message you are trying to communicate with the narrative visualization?**

  * I want to bring the reader's attention to world suicide rate. Poor, 75 plus year old male is the highest risk group to commit suicide. Sadly, this trend has remained consistent over the years even as health care service improved and overall GDP improved. We should put more resources on providing care and counseling to the high risk group. 

**Narrative Structure. Which structure was your narrative visualization designed to follow (martini glass, interactive slide show or drop-down story)? How does your narrative visualization follow that structure? (All of these structures can include the opportunity to "drill-down" and explore. The difference is where that opportunity happens in the structure.)**

  * I'm using an interactive slide show structure to help the user navigate. The whole story is narrated in 5 charts. Every chart has tooltip capability to allow the user to gain more information. Some charts allow the user to select data from a particular year.

**Visual Structure. What visual structure is used for each scene? How does it ensure the viewer can understand the data and navigate the scene? How does it highlight to urge the viewer to focus on the important parts of the data in each scene? How does it help the viewer transition to other scenes, to understand how the data connects to the data in other scenes?**

   * The main theme of this story, "World Suicide Rate", remains on the top left of the scene so user knows that the main topic runs through all scenes. 
   * The top center of the scene shows the title of the graph. This highlights the sub-topic of the what the current scene tries to convey. 
   * In the left part of the scene is a text panel providing more some more background of the message we are trying to convey.  
   * In the middle part of the scene is the actual chart displaying the data. The chart takes up the largest area of the screen to grab the user's attention. When appropriate, the chart also displayes axies so the user can quickly grasp the dimension of the data. In some charts, there's a slider so the user can select data from a particular year.
   * In some charts, it also include annotations to draw the user's attention to a particular part of the scene
   * Each scene uses the same template so the user can quickly orient themselves and connect the scenes. It toggles the current page number to indicate which part of the story the user is on. 


**Scenes. What are the scenes of your narrative visualization? How are the scenes ordered, and why**

   * The story starts from a high level scene depicting the overall world suicide trend from 1985 to 2016. Then it displays the world suicide rate per country per year. Then it follows the suicide rate per GDP, per age, and per sex. The scene is ordered such that the user is introduced from a high level view and gradually to lower level details that relates to suicide rate. 


**Annotations. What template was followed for the annotations, and why that template? How are the annotations used to support the messaging? Do the annotations change within a single scene, and if so, how and why**

   * The annotations has 3 components: note, subject, and connector. Note contains text that highlights the event; Subject points out the location of the event on the graph; Connector connects the note and the subject together. This template helps the user understand the highlight point, and the event associated with highlight. 

   * The annotations again help support messaging by pointing out the highlighted event and providing text to highlight the event. 

   * The annotations remain the same within a single scene. However they do appear few seconds later than the chart to help user notice them.


**Parameters. What are the parameters of the narrative visualization? What are the states of the narrative visualization? How are the parameters used to define the state and each scene?**

   * The parameters are the page numbers and each page number are linked to a unique state. When the user clicks on the page buttons, the current page number changes and thus the state changes and the scene is updated. 
   * In some particular states (pages) there are sliders that lets the user select data from a particular year. This will update the chart displaying data


**Triggers. What are the triggers that connect user actions to changes of state in the narrative visualization? What affordances are provided to the user to communicate to them what options are available to them in the narrative visualization?**

   * The triggers for each page are the act of clicking the page buttons. Affordance is provided by darkening the buttons when the users hover their mouse over them. The buttons stay dark if the user actually clicked the buttons indicated the current page is selected. 
   * The triggers for the sliders are when the user drag the slider. Affordance is provided by labeling the current mark on the slider.

