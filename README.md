# WOW Quiz

Welcome to my World of Warcraft Quiz!

(Developer: Daniel Elde-Johansson)

![Mockup image](assets/readme_images/Project2Mockup.jpg)

[Live webpage](https://daniele-j.github.io/WoW-Quiz/)

## Table of Content
1. [Introduction](#Introduction) 
2. [Project Goals](#project-goals) 
    1. [User Goals](#user-goals) 
    2. [Site Owner Goals](#site-owner-goals)
3. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
    4. [Site Owner Stories](#site-owner-stories)
4. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Fonts](#fonts)
    3. [Structure](#structure) 
    4. [Wireframes](#Wireframes)  
6. [Technologies](#Technologies)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
7. [Features](#features)
    1. [Start screen](#Start-screen)
    2. [Footer](#footer)
    3. [Quiz over screen](#quiz-over-screen)
    3. [Contact form](#contact-form)
8. [Testing](#validation)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [JavaScript Validation](#javascript-validation)
    4. [Accessibility](#accessibility)
    5. [Performance](#performance)
    6. [Devices](#Devices)
    7. [Browser compatibility](#browser-compatability)
    8. [Testing user stories](#Testing-user-stories)
9. [Bugs](#Bugs)
10. [Deployment](#deployment) 
    1. [EmailJS API](#emailjs-api)   
11. [Acknowledgements](#acknowledgements)

## Introduction

Welcome to my World of Warcraft Quiz, There is 15 questions to prove that you have knowledge about World of Warcraft.

## Project Goals

### User Goals

* Finding a  WoW quiz. 
* Having fun.
* Testing your knowledge.

### Site Owner Goals

* Creating a fun and knowledgeable game that users will want to improve on until learning it all. 
* The game should be fully responsive to be able to be played on different devices.

## User Experience

### Target Audience
- casual gamers
- people who like World of Warcraft
- people looking to test there knowledge

### User Requirements and Expectations

* A simple and easy system
* Links and functions that work as expected
* A simple way to contact the developer
* Easy, and fun to play


### User Stories
1. As a user, I want to test my general knowledge
2. As a user, I want feedback on my correct answers
3. As a user, I want to know what the score i got
4. As a user, I want to give feedback and try get other questions in
5. As a user, I want confirmation that my feedback was sent

### Site Owner Stories
8. As a site owner, I want users to be able to find us on social media.

## Design

### Design Choices

The Game was design so the picture can show the user what type of quiz it is, and to test there knowledge.

### Fonts

Sans-serif Was used through the whole website to make everything look the same.

### Structure

The page is structured in a well know, recognizable, user friendly, and easy to learn way.

* Introduction so you know where u are.
* instructions so you know what to do.
* social links and feedback bottom left so you can find us.

### Wireframes

### Wireframes

<details><summary>Home</summary>
<img src="assets/readme_images/homewire.jpg">
</details>
<details><summary>Contact</summary>
<img src="assets/readme_images/contactwire.jpg">
</details>


## Technologies Used

### Languages
- HTML
- CSS
- JavaScript

### Frameworks & Tools

* GitHub
* Gitpod
* Balsamiq
* Font Awesome
* Favicon<span>.</span>io
* Lighthouse
* W3C Markup validation service
* W3C Jigsaw CSS validation service 
* WAVE WebAIM web accessibility evaluation tool
* EmailJS

## Features
The site consists of two pages and seven features

### Start screen
- Provides an option to choose between three different game difficulties.
- User story covered: 

<details><summary>Start screen</summary>
<img src="assets/readme_images/startscreen.jpg">
</details>

### Footer
* Consists of a section providing social media links and a link to the contact form
* User story covered: 

<details><summary>Footer</summary>
<img src="assets/readme_images/footer.jpg">
</details>


### Quiz over screen
* Shows the score.
* Shows a restart button 
* User stories covered: 

<details><summary>Game Over Screen</summary>
<img src="assets/readme_images/endscreen.jpg">
</details>

### Contact form
* A way for the user to provide feedback
* A way for users to provide there questions to the quiz
* User story covered  

<details><summary>Contact Form</summary>
<img src="assets/readme_images/feedback.jpg">
</details>


## Validation

### HTML Validation
The W3C Markup Validation Service was used to validate the HTML of the website. All pages pass with no errors no warnings to show.
<details><summary>Home</summary>
<img src="assets/readme_images/htmlvalidation.jpg">
</details>
<details><summary>Contact Us</summary>
<img src="assets/readme_images/contactvalidation.jpg">
</details>

### CSS Validation
The W3C Jigsaw CSS Validation Service was used to validate the CSS of the website. When validating the page as a whole, the validator shows some errors linked to Bootstrap v5.0. When validating just my custom CSS it passes with no errors.

<details><summary>Full page</summary>
<img src="assets/readme_images/fullpagecss.jpg">
</details>
<details><summary>style.css</summary>
<img src="assets/readme_images/css.jpg">
</details>

### JavaScript Validation
JSHint Static Code Analysis Tool for JavaScript was used to validate the Javascript files. No significant issues were found.
<details><summary>game.js</summary>
<img src="assets/readme_images/javavali.jpg">
</details>
<details><summary>feedbackjs</summary>
<img src="assets/readme_images/feebackvali.jpg">
</details>

### Accessibility
The WAVE WebAIM web accessibility evaluation tool was used to ensure the website met high accessibility standards. All pages pass with 0 errors.

<details><summary>Home</summary>
<img src="assets/readme_images/wavehome.jpg">
</details>
<details><summary>Contact</summary>
<img src="assets/readme_images/contactwave.jpg">
</details>

### Performance 
Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website.

<details><summary>Home</summary>
<img src="assets/readme_images/lighthousehome.jpg">
</details>
<details><summary>Contact</summary>
<img src="assets/readme_images/lighousecontact.jpg">
</details>

### Devices 
The website was tested on the following devices:

* Iphone 16
* Samsung galaxy

In addition, the website was tested using the Google Chrome Developer Tools Device Toggling option for all available device options.

### Browser Compatability
The website was tested on the following browsers:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge


### Testing user stories

1. As a user, I want to test my general knowledge

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Website | Press Start  | Quiz to start   | Quiz started |


<details><summary>Screenshots</summary>
<img src="assets/readme_images/testing1start.jpg">
<img src="assets/readme_images/testing1quiz.jpg">
</details>

2. As a user, I want feedback on my correct answers

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Quiz | Press answer   | Green when right  | Green when right |
| Quiz | Press answer | Red when wrong but shows right green answer| Red when wrong|

<details><summary>Screenshots</summary>
<img src="assets/readme_images/testing2right.jpg">
<img src="assets/readme_images/testing2wrong.jpg">
</details>

3. As a user, I want to know what the score i got

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Quiz | Show results | To See results after quiz  | Result shown after quiz |

<details><summary>Screenshots</summary>
<img src="assets/readme_images/testing3.jpg">
</details> 

4. As a user, I want to give feedback and try get other questions in

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Feedback | Fill in form  | To form to get sent  | Form get sent |


<details><summary>Screenshots</summary>
<img src="assets/readme_images/testing4.jpg">
</details> 


5. As a user, I want confirmation that my feedback was sent

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Feedback | Send in form  | Get a text showing it got sent  | Got a text showing it got sent  |

<details><summary>Screenshots</summary>
<img src="assets/readme_images/testing5.jpg">
</details>


6. As a site owner, I want users to be able to find us on social media.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer| Press socials in footer | Takes you to the website | Took you to the website |

<details><summary>Screenshots</summary>
<img src="assets/readme_images/socials.jpg">
</details>


## Bugs

| **Bug** | **Fix** |
| ----------- | ----------- |
| The score doesn't show after the quiz is done | Add score to showscore function |
| The answer did not turn green when picking right answer | Added higlight to select answer function|
| The answer did not turn red when picking wrong answer | Added higlight to select answer function|
| The restart button did not show when done with quiz | Added button to restart function|
| The contact page has overflow on smaller screen sizes | Change padding and margin sizes for smaller screens |


## Deployment

* The site was deployed to GitHub pages. The steps to deploy are as follows: 
  1. In the GitHub repository, navigate to the Settings tab 
  2. From the menu on left select 'Pages'
  3. From the source section drop-down menu, select the Branch: main
  4. Click 'Save'
  5. A live link will be displayed in a green banner when published successfully. 

* You can clone the repository by following these steps:
    1. Go to the GitHub repository 
    2. Locate the Code button above the list of files and click it 
    3. Select if you prefere to clone using SSH, HTTPS, or Github CLI and click the copy button to copy the URL to your clipboard
    4. Open Git Bash
    5. Change the current working directory to the one where you want the cloned directory
    6. Type git clone and paste the URL from the clipboard ($ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY)
    7. Press Enter to create your local clone.

    ### EmailJS API
1. Create an account at emailjs.com
2. Add new email service, make note of the contact_service id
3. Add a new email template, make note of the contact_form id
4. Go the the integration dashboard, make note of your user id
5. Load the EmailJS SDK in the head of your HTML file
6. In JavaScript create a function that listens to a submit event and then initializes the SDK with your user id (emailjs.init('YOUR_USER_ID');) and submits the form (emailjs.sendForm('contact_service', 'contact_form', this);)

## Acknowledgements

I would like to take the opportunity to thank:
* My mentor Mo Shami for his feedback, advice, and support.
* My Wife Agnes for her support, advice and help with the baby so i can take time for my project.
