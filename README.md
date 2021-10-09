# Match 3 Bells To Win

The purpose of this project is to showcase my javaScript skills and i did that by making my 
'Match 3 to win game'. This project aims to accomplish a click function for when the user clicks on a div. What happens is that 
the image is shown and that image is registered to see if that image is a bell icon. Once the user get's 3 bell 
icons or losses by getting 3 wrong guesses a function is called to calculate the answer and determin 
if the user get's a win point or a loss point. After the game is finished the user will have a reset button to press
which reset's the images and the player can play again. 

![Home-page](assets/images/Matchinggame.PNG)

![Home-page](assets/images/Matchinggame2.PNG)

## Features 

* Alert 
 + When a user first loads in, they will see a alert pop-up which will tell the user how to play this game. 

![Alert](assets/images/alert!.PNG)
  
***

* The Game Area
 + This section will allow the user to play the Matching game. The user will be able to click on a square box to 
   display a image.  
   + The user will be able to see how many guesses they have left whenever they click on the square box, an alert will show up and give the user a number between 1/3 depending on how many times they have guessed wrong.
 ![game-area](assets/images/game-area.PNG)
   


***

* Reset-button
   + The Reset-button on my page is located right below my game-area so that the user knows what the reset button is resetting.

![reset-button](assets/images/resetB.PNG)
***

* Scores

   + This section will allow the user to see exactly how many wins and losses they have got.
   + The scores section is located underneat the reset-button. 
   

![Scores](assets/images/Scores.PNG)
*** 

**Features Left to Implement**
 * header + footer + javaScrit
   + If i had more time i would like to style my page a bit more and polish it (make the header nicer) .
   + I will add a footer in my spear time to make this look more complete. 
   + I want to add a function where the user will have a pop-up when they win or loss. 

***
    
   ## Testing
   + I have tested all the functions by playing the game once i have implemented a new function, The first function i created was for an EventListener which gets activated once the game is fully loaded and this function sets of the other function which are the reset-button function and the getRandomImage function. I have fully tested out theys functions and i know the pros and cons of each function, the problem i still face but plan on fixing is that the getRandomFunction randomizes the images but it dose not garintee that all bell icons will load, There is another issue with this function, the user can just keep on clicking on one div and that will count as if the user clicked on different divs (which is not cheating since the princle of the game is still the same, but it's not as intended). Of course theys problems can be easily fixed with a bit of javaScript knowlege so im not too worried about it now but i still plan on fixing theys. I also had an issue with the caluclateAnswer function but i fixed it, the problem was in my switch case, my case 2 wouldnt work but i fixed that problem by excuting the code on the default case instead. The calculateAnswer function called the playerHasWon or playerHasLost depeanding on if the player won or not and i had alot of trail and errors with they's function but over a period of time i came accross arrow functions which helped me stop the game once the game has finished. I also used arrow functions for my resetGame function and i added some know features to my getRandomImages function.

   + I have confirmed that all my content is easily usable to the user by showing my website to someone else.
   + I have tested my website in different browser's such as: Microsft Edge, Chrome and Firefox.

   **Bugs** 
* UnSolved Bugs
   + The getRandomFunction randomizes the images but it dose not garintee that all bell icons will load, thats because the getRandommImages function only randomizes the images but dose not pick a set number before it randomizes the images a thus some images will not in cirtain times you play. 
   + The user can just keep on clicking on one div and that will count as if the user clicked on different divs, this is because the div dose not save the the current choice 
   *** 
**Validator Testing**
* HTML
   + No errors or warnings were found for all pages - index More or sign-up.
* CSS 
   + No errors were found but a warning with the contents of 'Imported style sheets are not checked indirect input and file upload modes' which doesn't relate to my CSS.
* Accessibility 
   + I have checked lighthouse and confirmed that my website is easily accessible to users.
   ![Lighthouse scores image](assets/css/images/Lighthouse.PNG)
**Unfixed Bugs** 
   + I can't move my iframe video to the left, I tried margin, padding, and floats but the only thing that worked was a one line style but the problem is that I cant use @media on it to set height and width, just couldn't connect my CSS to this element. 
   + If I had more time I would try and make this website a bit more responsive. 
   ***
   ## Development
* My website was deployed on GitHub pages, they are the steps I took:
   + In GitHub repository, I navigated to settings. 
   + I scrolled down to pages, I clicked on the link. 
   + In the source drop-down menu, I selected my branch as - main, and then I got the link to my website. 
   * Here is the link to my website - https://arminas19.github.io/Project1/ 
 ### Credits 
   **Content** 
   + I took Some of the code from the sign-up form the Love Running Project or 'Challenge'. 
   + I had some inspiration from the links and active class from the Love Running Project, but I didn't copy and paste I just wrote it myself.
**Media**
   +  I copy and Pasted some text from the officially EA Fifa 22 website - here is their link: https://www.ea.com/en-gb/games/fifa/fifa-22.
   + All my images were taken from this link: https://www.bing.com/images/search?q=fifa+22&form=HDRSC3&first=1&tsc=ImageHoverTitle.  
   + I also used google fonts and icons - link for that: https://fontawesome.com/v5.15/icons/comments?style=solid.
