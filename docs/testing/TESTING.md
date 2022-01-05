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
    7.1 



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
Using a combination of devices available to me, I checked all pages and found that the website reflowed correctly on diffrent screen sizes.  
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

