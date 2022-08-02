# Working-with-CSSSelector---Tag-and-Class
Assignment 2 W9D3 - SDA - Software QA Bootcamp

## Table of contents
* [Question](#question)
* [Answer](#answer)
* [Output Screenshots](#output-screenshots)

---
## Question
On the Facebook website, use CSSSelector with Tag and Class and use it to change the language of the webpage.
- STEP 1: Go to Facebook.com
- STEP 2: Right-click on any of the languages at the bottom of the webpage
- STEP 3: Click on Inspect and pick a language to locate the web element using the CSS Selector with Tag and Class
- STEP 4: Complete the language change flow


## Answer

I used a ["Facebook"](https://www.facebook.com/)
And Before running the code, there are some steps that need to take considered:


### First:
Setup Latest Web Driver for Chrome  Driver.
Donwload the necessary jar files:
- Selenium (Lastest).
- TestNG (Lastest).
- commander (Lastest).

### Second:
Add them as a library in the classpath of the project
- _click-reight on the file project >Build path > configure Bild path > Java Build Path > Libraries > classpath > add external JARs > Apply and close_.

### Third:
I opened the website, then take web elements, and then add them to the code I use cssSelector with Tag and Attribute as syntax:
`tag[attribute=value]`

I want to use them with Tag and Class as syntax: `tag.class'
but it can not be, because there are not unique.
 
<p align="center">
<img src="https://user-images.githubusercontent.com/48597284/182495230-62d8915f-f1d7-4cc0-b180-176c3e7f9ea4.png" width=60% height=60%>
</p>

---
## Output Screenshots:

<p align="center">
<img src="https://user-images.githubusercontent.com/48597284/182495961-72b80b58-cced-40d1-984b-bc01a1dd8ffa.png" width=80% height=80%>


https://user-images.githubusercontent.com/48597284/182496004-8ea8c90e-871b-4229-9556-44d3f765fca4.mp4
</p>
