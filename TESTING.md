# Hobby - Testing

This file was created on the second edition of this project. All issues in the assessment feedback form were carried out first, followed by any additional information that would be of benefit to the README & TESTING sections.

add image of finished site using [amiresponsive](https://ui.dev/amiresponsive)
add link to live site deployed on github pages

---

## CONTENTS

* [Automated Testing](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
  * [WAVE](#wave)

* [Manual Testing](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)

* [Bugs](#bugs)
  * [Solved Bugs](#solved-bugs)
  * [Known Bugs](#known-bugs)
 

---

## Automated Testing

The Automated Testing includes all the testing that is carried out by a program, like W3C HTML validation.

###  W3C Validator

👩🏻‍💻 View an example of a completed W3C HTML & CSS validation section [here](https://github.com/kera-cudmore/TheQuizArms/blob/main/TESTING.md#W3C-Validator)

The most popular HTML validator is [W3C](https://validator.w3.org/). There are two ways to validate the HTML for your first milestone - you can copy the live link for your site page and paste into the validate by URI field, or you can copy all the code for your page and paste this into the validate by direct input field.

#### **URI Input**

If you validate with your sites URL, you can run the validation and then copy the link from the address bar and insert the link here as your proof of validation.

![W3C URI Validator](documentation/milestone1-testing/w3c-uri-validatation.png)

#### **Direct Input**

If you validate with the code, you will need to screenshot the validation results and then link the image here.

![W3C Direct Input Validator](documentation/milestone1-testing/w3c-directinput-validation.png)

#### **CSS Validation**

CSS Validation can only be done by copying and pasting the CSS file contents into the direct input. Make sure that the checkbox for CSS is selected.

![W3C CSS Validation](documentation/milestone1-testing/w3c-css-validation.png)

### Lighthouse

👩🏻‍💻 View an example of a completed lighthouse testing section [here](https://github.com/kera-cudmore/earth-day-hackathon-2022/blob/main/TESTING.md#Lighthouse)

Lighthouse Testing is part of the Chrome Developer Tools. For more information on how to use this tool, please visit [chrome Lighthouse](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en#:~:text=Lighthouse%20is%20an%20open%2Dsource,how%20well%20the%20page%20did.).

You will need to run the Lighthouse testing on each individual page of your site, for desktop as a minimum. If you have time it would be great to also add in the mobile testing.

![Lighthouse Testing](documentation/milestone1-testing/lighthouse.png)

### WAVE

👩🏻‍💻 View an example of a completed WAVE testing section [here](https://github.com/kera-cudmore/earth-day-hackathon-2022/blob/main/TESTING.md#WAVE)

[WAVE](https://wave.webaim.org/) is an accessibility testing tool. I like to run this on each page of my site and take a screenshot of the results to add here. They have a website for testing and a Chrome extension.

![Wave Desktop](documentation/milestone1-testing/wave-desktop.png)

![Wave Exetension](documentation/milestone1-testing/wqave-extension.png)

## Manual Testing

### Testing User Stories

👩🏻‍💻 View an example of a completed user stories testing section [here](https://github.com/kera-cudmore/BookWorm/blob/main/TESTING.md#Testing-User-Stories)

This is where you will test the user stories you created in the README against your site. I like to use a table for this section - I create a column for the user stories goals, how these have been achieved and I use the third column to add any supporting images.

### Full Testing

👩🏻‍💻 View an example of a completed full testing section [here](https://github.com/kera-cudmore/TheQuizArms/blob/main/TESTING.md#Full-Testing)

Full testing can be tedious, so it is great to try and break this part up into smaller chunks and do a bit at a time. Full testing is when you go through the site and test every single thing that can be tested. So for example you would test that all links in the navbar correctly redirect the user to where there are supposed to go. A table is the perfect way to display this information.

## Bugs

### Solved Bugs

| # | Bug | How I solved the issue |
| :--- | :--- | :---|
| 1 | The README file had additional content that pointed to the UX of another repository for a different project. | I removed the link from aforementioned UX & and additional typos that existed in the README file. I then ensured the rest of the file contained only my own original material & acknowledged credits for same. |
| 2 | The closing brackets were missing from one of the link elements in the heading area. | I added closing brackets to link elements. I ensured this was carried out across all html files as the skeleton of each file was copied from the original index.html. |
| 3 | index.html had an extra </i>. | I removed this tag & ensured this was carried out across all html files as the skeleton of each file was copied from the original index.html. |
| 4 | A stray end tag div in index.html. | Removed stray div. |
| 5 | Duplicate of defined class attribute in section of signup.html. | I removed this unnecessary class attribute. |
| 6 | Duplicate ID input-field in signup.html | I removed the duplicate of the defined class attribute in the section of signup.html. I changed the name of each ID to reflect the use of the input field. I then added these names to the style.css, so as to avoid creating any additional bugs. |
| 7 | More descriptive title tag needed | I elaborated on title tag of each html page, & described each once accordingly. |

- Once all of the solutions were carried out, I reviewed each issue to ensure all corrections were applied & no further issues were occurring.

### Known Bugs

| # | Bug | |
| :--- | :--- | :---|
