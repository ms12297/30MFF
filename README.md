# 30MFF
CommLab - Assignment 1
- Project Name: 
CommLab-Assignment1-30MFF Website

- Project Description: 

I created a website from scratch to showcase the 30 Minute Film Festival film I made with my partner. This project is the first assignment for the course Communications Lab at NYUAD. The overall concept is to utilize the knowledge of HTML, CSS, and JavaScript in order to make a fully functional and organized website. I was striving to create an interactive and aesthetic experience for my users. I planned to include a sidebar, a slideshow showcasing some shots from the film, and flipping images for the cast that would reveal the cast's role when flipped. 

- Process: 

The first step in the process of making my website was to create a backbone using HTML. I found making classes especially useful in this assignment and realized their importance because it is easy to target them in the CSS file. I also used an online stylesheet library to include icons in order to replicate my initial wireframe. The hierarchy of div elements is as follows: wrapper; container; sidebar, main, header, footer. After this structure was complete, I made a CSS file and linked it to my HTML document. I will summarize the most technical aspects of the CSS code here. First, I added details to the sidebar in order to ensure that my website is interactive. I did this by reserving dimensions for the sidebar if it is active and removing that space from the webpage when the sidebar is toggled off. The latter allows the main, header, and footer to occupy 100% of the page. I also added a transition speed to the toggle in order to make the transition smooth and more refined. I added color changes based on mouse hover on the different icons I use in the website through the CSS code. I used online color generators to implement the colors I had planned to use. For the main, I gave every section div a box that has a shadow effect on the edges. Furthermore, upon mouse hover, it changes colours to add a little more interactivity into the webpage. One problem I had was that I could make the footer have a fixed position but not the header. I realized that this was because I declared the header before the main in the HTML document and this is why the main would hover over the header in the webpage. That is why I switched the order of the main and the header later on. Finally, using JavaScript, I added the toggle functionality to mouse click on the div bars that contains the bars icon for the sidebar.

- Reflection/Evaluation:

Not all my expectations were met. I could not implement the slideshow or the flipping images as I had initially planned because making the sidebar took more time than expected. This is why I could not make my website as interactive as I wanted to it to be. However, I think now that the simplicity in the final product is one of its primary strengths. Also, I managed to code in CSS more effectively than I thought I could. The flexbox functions make everything easier to control. Unexpectedly, I did not need to utilize JavaScript as much as I thought I would. I only needed it to add the toggle function for the sidebar. In the future, I plan to use it to add the slideshow and flipping image functionaltiies. Overall, I would say I have learned the basics of HTML, CSS, and JavaScript from this project.  
