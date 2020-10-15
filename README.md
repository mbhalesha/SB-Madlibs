# Madlibs
 
https://mbhalesha.github.io/SB-Madlibs/.

I have created a Madlibs game using Python and Flask. I have defined the Madlibs stories and it will generate the resulting story from a set of answers. 

For debugging, I used ipython as well as the Flask Debug Toolbar. The form route asks all the questions required by the story and the /story route shows the resulting story for those answers. I have used template inheritance with base.html.

I have added a feature in which the user can choose a template and be directed to a page that prompts for the list of story questions. That will then go to the page that shows the generated story.

I have added some CSS and have stored the CSS file in a static/ directory and reference it so that Flask will serve it up.
