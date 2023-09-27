# Hang in There  

### Abstract:
[//]: <> (Briefly describe what you built and its features. What problem is the app solving? How does this application solve that problem?)
We built a webpage that loads a random poster that contains: an image, a quote, and a title to represent the quote. The idea is that when you select a random poster, the webpage will reload a new random image, quote and title. If you click, 'make your own poster', you can input an imageURL, title and quote and load it to have your very own poster. There is also saving functionality as well so that you can save any of the random autopopulated posters or the one you created and the webpage stores all of them. If you double click a saved photo, it will delete it, so you can remove it from your saved collection if you want to do so. This solves the problem of having to create your own poster and randomly selects a photo and quote to do so.

### Installation Instructions:
[//]: <> (What steps does a person have to take to get your app cloned down and running?)
To get the app cloned down and running, you need to copy the link from github in the code drop down menu (SSH) and in your terminal, git clone and paste the link. When you are in the correct directoy, the directory you just cloned down, you can open VS code by typing code . and within your terminal, you can use open index.html to view the application. 

The app can also be accessed live at: https://ericahagle.github.io/hang-in-there/

### Preview of App:
[//]: <> (Provide ONE gif or screenshot of your application - choose the "coolest" piece of functionality to show off.)

<img width="1440" alt="Poster with picture of a squirrel, a title of 'Mindfulness', and a motivational quote of 'When you have a dream, you've got to grab it and never let go.'" src="https://github.com/ericahagle/hang-in-there/assets/133910120/662c10db-5381-4f35-8770-91e371431bb9">

<img width="1440" alt="A group of saved motivational posters" src="https://github.com/ericahagle/hang-in-there/assets/133910120/ec5d7dd0-34db-410e-99b2-795cf6055c81">


### Context:
[//]: <> (Give some context for the project here. How long did you have to work on it? How far into the Turing program are you?)
We are currently on week 2 of Mod 1. We started the project on tuesday and it is due on Sunday but due to schedules on my part (Emalee), we tried to get it done before the weekend. We were able to complete through iteration 4 before end of day on friday but it required a lot of time and persistence. 
### Contributors:
[//]: <> (Who worked on this application? Link to their GitHubs.)
Erica Hagle and Emalee Poellot worked on this project (Erica : https://github.com/ericahagle and Emalee : https://github.com/em2396 )

### Learning Goals:
[//]: <> (What were the learning goals of this project? What tech did you work with?)
The learning goals were to create DRY Javascript and build functionality with already created CSS and HTML (understanding the connection betweeen the three languages) and to beging to understand what it's like to work collaboratively. We primarily worked with JS because the HTML and CSS were already coded and created for us. 

### Wins + Challenges:
[//]: <> (What are 2-3 wins you have from this project? What were some challenges you faced - and how did you get over them?)
1. We finished the project in a timely manner which seemed impossible, but we overcame a lot of the blocks we had.
2. We worked well together. There were times when both of us were working on the code seperately (due to scheduling or just needing a break from the computer) but we did most of the work together and while it can be frustrating working on something in two different places, we overcame that with the help of Tuple, and were able to problem solve very well together to get the functionality we needed.
3. Overcoming challenges is a win in itself. When we stared at a piece of code for an hour and couldn't figure it out, just to have an epiphany or some slight refactoring that made the code work was a huge win for both of us.
One challenge we faced: During iteration zero, we created functionality so when the page was loaded, a picture, title, and quote was loaded but wouldn't change when you clicked change poster. This was because the currentPoster variable wasn't updating every time the changePoster function was being invoked (or the button was being pressed). It took us some time and refactoring of our functions to get the currentPoster to update at every click of the page. It was also a little daunting looking at the project and trying to see the finish line.
