INDEX.HTML
1. In index.html, change the text of the element with id="profile-name" from "Israel Tech Challenge Pre-Course'' to your full name. Next, add a subtitle below the title. The text of the subtitle should say "ITC Fullstack Development." For the font family of your project, choose a font from Google fonts (https://fonts.google.com/) or attach one of your choice to the styles file using @font-face rule. Otherwise, add styling of your choosing to the page. Throughout this assignment, please add your code for the styling to the "style.css" file. Also, throughout this assignment, we expect you to make your styling look professional and eye-catching.
2. In index.html, remove the "Visit ITC" link. Add a navigation bar at the top of the page. This navigation bar should be fixed to the top, always taking 100% of the width, and no matter if you scroll, it should always be visible. The navigation bar must have three links: "Home", "About", and "Contact". Use an <a> tag to link to the pages. Please add the style of your choosing to the navigation bar and links.
3. Add three clickable elements nested inside the element that has a ‘card’ class. These three clickable elements should be inside an unordered list as list elements. Each one of this list elements should be clickable. Link one to your LinkedIn account. Link another to your Github account. Link the third to your StackOverflow account. If you don't have accounts for each of those, please create them (www.linkedin.com, www.github.com, www.stackoverflow.com). Make sure you have a photo uploaded to your account profile for Github. For the clickable elements, use icons from Font Awesome (www.fontawesome.com).
4. In main.js, update the value of GITHUB_URL to your Github profile. Make sure you write the proper link. Then, change the code so that it displays your Github profile picture instead of the ITC Github profile picture. Do the same for your name so that it displays your profile name from your Github account instead of hardcoding your name.
5. On your home page, add functionality to the card containing your profile photo and buttons. When the user hovers over the card, have the card respond with some sort of animation. Trigger a second, more elaborate animation, upon clicking the card.
See the image ‘index.png’ in the ‘Examples’ folder for reference.
There should be two animations in total, one on hover, and one on click.
CONTACT.HTML AND ABOUT.HTML
6. In these two files, add the same navbar from your home page to each of the new pages you created. Add some basic HTML to each page so that the about page has a title that says "About" and the contact page has a title of "Contact".
7. Inyournavbar,connectthenavbarlinkstotheirrespectiveHTMLpages.Whenyouclickonthe links, your browser should display the corresponding HTML page.
ABOUT.HTML
8. On the "About" page, create a section that includes the following information: describe why you are interested in coding, your educational and career experiences, and your personal interests. Please style and layout the page as you choose.
9. Add another section below what you created in the previous step. In this section, write where you were born and the cities in which you have visited. There should be at least 3 cities in total. If you have visited two cities or less, complete the list with other cities you would like to visit.
10. Add two buttons: "Previous" and "Next" below the map. Clicking the "Next" button should change the pointer to the next city listed on your about page (i.e., a city you have lived in or want to visit). When the first of the series of locations is selected, the "Previous" button should disappear or be disabled, and when the last location is selected, the "Next" button should be the one blocked. Otherwise, both buttons should be visible. We encourage you to implement this using only one iframe.
To summarize the behaviour of points 9 and 10, please give a look to the animation provided inside the examples folder, under the filename maps_behavior.gif.

CONTACT.HTML
11. Sign in for a free account in Formspree. (link). Formspree is a free service that allows us to create forms, and receive the information in our email. Create a new project for it named “ITC Precourse”. Don’t worry, we are attaching snapshots on how to solve this part.
12. After grabbing the endpoint, on the "Contact" page, create a contact form. This form would use the Formspree endpoint to post the information. The form should contain inputs for first name, last name, email, comment. There should be an additional input type where the user can enter additional information in a non text form. All fields except the "last name" field should be required.
Add a submit button to your form. When the submit button is clicked, you should actually submit your form, and get an email with the information of your submitter (provided by Formspree).
Double check that this functionality is working properly before submitting.
13. The submit button should not be functional and should look disabled as long as the required fields are not filled in.
See the image ‘contact.png’ in the ‘Examples’ folder for reference. 

IN ALL THE PAGES (INDEX, ABOUT, CONTACT)
14. On all of your pages, put a footer at the bottom of the page. The footer should contain the same links as your navbar. It also should contain a sentence saying: "This page was built using: HTML, CSS and JavaScript". The words "HTML", "CSS", "JavaScript" should be stored in an array and generated on the website rather than be "hard-coded". The word “and” should not be in your array, but it should be in your sentence.
Create the array in a way that if more languages were added to the array, the code wouldn’t need any extra modifications.
Your solution needs to work with all of the following arrays interchangeably:
a. constcodingLanguages=["HTML"]
b. constcodingLanguages=["HTML","CSS","JavaScript"]
c. const codingLanguages = ["HTML", "CSS", "JavaScript", "Python", "Java", "C++"]
The original array must preserve its original characters without modifications (no adding spaces, commas, or any other character).
The sentence generated should have a space after each comma, except for the last element, which should have " and " before. e.g. ["HTML", "CSS", "JavaScript"] => '''This website has been created with: HTML, CSS and JavaScript'