# Testing Document

This document details how Hertford and Ware Fundraisng group website was tested to ensure it is complient and meets good user experiance (UX) whilst being as accessible to all its users who visit the site.

## Table of contents

1. [Testing approach](#testing-approach)  
2. [Validation Testing](#validation-testing)  
    2.1 [HTML Validation](#html-validation)  
    2.2 [CSS Validation](#css-validation)  
3. [Browser Reflow and Responsive test](#browser-reflow-and-responsive-test)  
4. [Link testing](#link-testing)  
5. [Tab order test](#tab-order-test)  
6. [Landmarks test](#landmark-test)  
7. [User stories testing from the UX section](#user-stories-testsing-from-the-ux-section)  
    7.1 [First time user](#first-time-user)  
    7.2 [Eeturning visitor](#returning-visitor)  
    7.3 [Site owner](#site-owner)  




## Testing Approach

## Validation testing
### HTML Validation
-  Homepage  
    ![W3C Validator result](testing-images/validation-html-homepage.png)  
-  About us  
    ![W3C Validator result](testing-images/validation-html-about.png)
-  Fundraise  
    ![W3C Validator result](testing-images/validation-html-fundraise.png)
-  Events and collections  
    ![W3C Validator result](testing-images/validation-html-events-and-collections.png)
-  Contact us  
    ![W3C Validator result](testing-images/validation-html-contact-us.png)
-  Donate  
    ![W3C Validator result](testing-images/validation-html-donate.png)
### CSS Validation
Two random pages were selected as the validator is assessing the CSS which is loaded on every page.
Both pages showed a Pass.
-  HomePage  
    ![W3C Validator result](testing-images/validation-css-homepage.png)
-  Donate  
    ![W3C Validator result](testing-images/validation-css-homepage.png)  

## Browser Reflow and Responsive test
Using a combination of devices available to me, I checked all pages and found that the website reflowed correctly on different screen sizes.  
A programme called Browserling was also used to test and simulate an operating system back to Win 7 and running IE11.
All simulated screens rendered the website correctly. [example of browserling, win7 firefox 90](https://www.browserling.com/browse/win7/firefox90/https://jhodgkins.github.io/MSP1-Fundraising-Group/index.html 
)  
## Link testing
All links on the site were tested to ensure that internal links behaved correctly, and that external facing links opened a new tab as expected.
A screen reader was used during these tests on PC and MAC to ensure that the Sr-Only help text classes which have been applied were announced correctly by the screen reader software.  
an example of the code is shown below:  
```
<a class="btn btn-outline-secondary" href="//widgets.justgiving.com/Button/Redirect?p=eyJJZCI6Ijg3MmFmYzc4LWFkMDYtNDdmMS1iNzI2LTEwODQzZjliYjhkOSIsIkNoYXJpdHlJZCI6MjI2MSwiU2l6ZSI6InMiLCJSZWZlcmVuY2UiOiIiLCJUeXBlIjoiRG9uYXRlIn0=" target="_blank" rel="noopener">Donate through Just Giving <span class="sr-only">(opens Just Giving official site in a new window)</span></a>
```
## Tab order test
Accessibility insights was used to test tab order on pahes.  
All focusable elements recieved focus as expected.  
![Tab/Focus Stop capture](testing-images/tabstop-screencapture.png)

## Landmarks test
Screen reader users use landmarks to highlight sections on the page, these are implimented using HTML5 semantic markup.  
![Landmark capture](testing-images/landmark-regions-screencapture.png)  

## User stories testing from the UX section

### First time User

-  __As a first-time site visitor to the website, I want to understand what the site’s purpose is so that I can decide if it interests me__  
When a new visitor arrives at the site, they will immediately see the logo which reads ‘Hertford & Ware Group’, with a supporter logo placed in proximity which reads ‘In support of Guide Dogs’.  
Just below this our large Hero banner image which grabs the users attention and reads ‘Hertford & Ware Fundraising Group’ which is followed by introductory text.  
A new visitor would be immediately aware of the websites purpose using these elements.  
![User stories q1](testing-images/testimage-hero.png)  

-  __As a first-time site visitor, I want to be able to easily navigate the site so I can find the areas I am interested in.__  
Located on every page in a standardised place, top right-hand side of the screen are six links, these are clearly visible with a highlighted border below the Homepage link to show its active state.  
Move mouse to the top right and select a link or tab through the navigation links.  
![User stories q2](testing-images/testimage-navigation.png)  

-  __As a first-time site visitor, I want to immediately understand what areas the group covers so that I can determine if I am local to the group.__  
The Hero banner plays an important role by showing the towns that the group cover, there is also a short introduction titled Who we are just below the Hero image which details information relating to the areas in which the group cover.  
When page loads, eyes should be drawn to the large heading level 1 group name.  
![User stories q3](testing-images/testimage-hero.png)  

-  __As a first-time site visitor, I want to know more about the fundraising group__  
Located just below the Who are we paragraph is a link to a more detailed explanation, alternatively the visitor can use the main navigation and select About us  
When page loads, scroll a small amount and select Find out more about us.  
When page loads move mouse or press tab key two times to land on the About us navigation link.  
![User stories q4](testing-images/testimage-who-we-are.png)  

-  __As a first-time site visitor, I want to find out how to volunteer__  
The main navigation holds a Fundraise link which leads to information about fundraising.  
Homepage, there is a large full width card with a Fundraise with us heading and link to take the user to the fundraise page.  
Events & collections and Donate pages have a card above the footer with a Fundraise for us heading and link to the fundraise page.  
![User stories q5](testing-images/testimage-fundraise-with-us.png)  

-  __As a first-time site visitor, I want to get a feel of what to expect if I want to volunteer for the group__  
Using the navigation to select events and collections the user will be taken to a page where it details what happens at events and collections including a photo gallery to view.  
![User stories q6](testing-images/testimage-fundraise-page.png)  

-  __As a first-time site visitor, I want to be able to donate to the group__  
Select the Donate link in the main navigation which will show all ways to donate to the cause.  
![User stories q7](testing-images/testimage-donate-page.png)  
 
-  __As a first-time site visitor, I want to be able to ask a question__  
Located in the main navigation is a link to the contact us page, there is also a section in the footer which is present on all pages which says Got a question.  
![User stories q8](testing-images/testimage-got-a-question.png)  

### Returning Visitor
-  As a returning visitor, I want to see the latest upcoming event  
    Located on the homepage a returning visitor will be able to see the next upcoming event or collection.,  

-  As a returning visitor, I want to know what roles are currently available within the group
-  As a returning visitor, I want to be able to ask a question regarding a service or collaboration
-  As a returning visitor, I want to view photos of past events or collections
-  As a returning visitor, I want to visit the fundraising groups social media pages
-  As a returning visitor, I want to know how to book a talk from a speaker/GDO/Puppy walker for my group, school
### Site Owner
-  As the site owner, I want visitors to find information about upcoming events or collections
-  As the site owner, I want visitors to understand what the groups fundraising goals are, to find out more about the main charity and how it helps visually impaired people.
-  As the site owner, I want the site visitors to be able to contact the group regarding a service or ask a general question
-  As the site owner, I want site visitors to be able to donate to the group easily.

