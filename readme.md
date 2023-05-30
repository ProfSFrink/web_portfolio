# __Web Projects Portfolio__

This is a collection of the Web projects that are part of my portfolio thus far, this is basically anything that makes use of HTML, CSS and / or JavaScript. They were all developed in Visual Studio Code and utilise HTML5, CSS3, Bootstrap5 and JavaScript.

&nbsp;

## __Personal Portfolio Website__ [(CODE)](https://github.com/ProfSFrink/web_portfolio/tree/master/personal_portfolio_website_javascript)

---

### __IMPLEMENTS: HTML, CSS, JavaScript, Images, Web Forms, Events, SlideShow, Navbar, Responsive Web Design, UI__

This is the source code and accompanying media for my personal portfolio website which can be found [here](www.stevenpartlow.com). The site was coded from scratch using Visual Studio Code. The layout for the site is the standard layout which starts with a navbar, followed by a jumbotron style site header with scrolling text, then the site uses the two column, two row approach for the bio and github links in the top row with the skills and linkedIn sections below, followed by the footer then a button to bring up the contact form, which makes use of formspree to store any information entered by the user. The site is responsive and works on both desktop and mobile devices. The header also contains a simple slideshow made with JavaScript, I import the GT Walshiem Pro font from the the font awesome library so it can be used by CSS.

&nbsp;

## __JavaScript Tic Tac Toe Game__ [(CODE)](https://github.com/ProfSFrink/web_portfolio/tree/master/TicTacToe)

---

### __IMPLEMENTS: HTML, CSS and JavaScript, Arrays, Functions, Logical Operators, Canvas, Audio, Images__

A Tic Tac Toe game running on JavaScript, a simple web application that allows the user to play a game of Tic Tac Toe against the computer. The game itself is a 3 by 3 HTML table with some simple CSS styling, the game itself run off JavaScript. The main game logic is within the function placeXOrO which firstly checks if the square being clicked on is empty, then determing which players turn it is, moves are recorded within an array this is to allow checking of win conditions. A function called computersTurn is used for the computer to take their turn, after which we check for a win by using the checkWinConditions function, this functions has a sub fuction called arrayIncludes in which we pass in three square locations if all return true then we have a winner, then the drawWinLine function draws a win line across the three winning squares, before playing the winner audio and reseting the game so the user can play again.

&nbsp;

## __JavaScript Calculator__ [(CODE)](https://github.com/ProfSFrink/web_portfolio/tree/master/calculator)

---

### __IMPLEMENTS: HTML, CSS and JavaScript, Functions, Logical Operators, User Interface Design__

A calculator application that runs on JavaScript in a browser, it allows the user to add, subtract, multiply and divide and also supports decimal places. The calculator accounts for the accidental clicking of the decimal button to prevent bugs and also removes trailing zeros from any number, the calculator is styled using CSS. The buttons are given HTML class names such as operators, equals-sign, decimal and all clear and these names can then be used by the event listeners in the JavaScript code so we know which button the user clicked on.

&nbsp;

## __JavaScript ToDo Appication__ [(CODE)](https://github.com/ProfSFrink/web_portfolio/tree/master/todo_app)

---

### ___IMPLEMENTS: HTML, CSS and JavaScript, Functions, Logical Operators, Arrays, Local Storage, User Interface Design__

A ToDo application that runs on JavaScript in a browser. It simply allows the user to type the name of a task into text input box at the top of the page and simply click the add button to add it to the list, items can be removed from the list which is stored locally in the browser cache.

&nbsp;

## __Pizza Ordering Application__ [(CODE)](https://github.com/ProfSFrink/web_portfolio/tree/master/Pizza_Project)

---

### ___IMPLEMENTS: HTML, CSS and JavaScript, Functions, String Concatenation, Console, Logical Operators, Arrays, User Interface Design__

A JavaScript application that allows the user to pick a pizza size and toppings and then calculate the cost, the reciept is stored as a string and as the user add elements to their order, these elements are added to the string, which is updated through concatenation and contains HTML tags this is then displayed at the end of the script, the JS code also calculates the total order amount based on pizza size and number of toppings chosen, it also gives the user one topping for free and the code accounts for this, again the app uses basic HTML styling.

&nbsp;

## __Simple Hobby Blog Site utilising Bootstrap__ [(CODE)](https://github.com/ProfSFrink/web_portfolio/tree/master/bootstrap4_project)

---

### __IMPLEMENTS: HTML, BOOTSTRAP and JavaScript, Responsive Web Design__

A simple hobby blog site developed in Visual Studio Code using bootstrap, makes use of bootstrap features such as cards and badges.

&nbsp;

## __Gaming Blog__ [(CODE)](https://github.com/ProfSFrink/web_portfolio/tree/master/One-Page%20Website)

---

### __IMPLEMENTS: HTML, CSS and JavaScript__

This was the first proper website I created, which I am keeping here, a very simple gaming blog I created in Visual Studio Code using HTML, CSS and JavaScript, it was to the cover the Nintendo Switch game Trianlge Strategy which I was playing at the time.
