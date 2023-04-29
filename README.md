# Pen-Testing-Live-Targets-2023
Pen Testing Live Targets Codepath Spring 2023


## GREEN
CROSS-SITE SCRITPING(XSS) 
inject a simple XSS line of code on the page with the form. Once user logins in a popup alert box will appear with 
the message. 

![green_XSS](https://user-images.githubusercontent.com/55906428/235280733-0b19150f-5912-4609-a11e-f105aa4a2e6b.gif)


CROSS-SITE-SCRIPTING GREEN TARGET First I logged in to check the user account. I noticed that you can see the feedback inside the account after login. Then i tested the contact page to see if that shows anything after login in. I send a feedback on all targets and I didnt get any pop ups. After numerous attempts I gave up. I returned after an hour and I logged in the pop ups appeared in the green target.

![green_Cross-Site-Scripting](https://user-images.githubusercontent.com/55906428/235255854-fc002999-b0a6-4eae-a20c-0dee8f2ac763.gif)

## BLUE
SQLi : inject a sql instead of a the Salesperson' ID Number revealed a lag in response so that indicates
there is a vulnerability in the code to access the Database.

![blue_SQLi](https://user-images.githubusercontent.com/55906428/235257713-da306cda-09f3-4c47-91f1-041b93e5f3fd.gif)


## RED
IDOR : revealing restricted user accounts. 
Hidden accounts are displayed by simple iteration in the URL parameter section.

![red_IDOR](https://user-images.githubusercontent.com/55906428/235280122-986b0ec1-8c2a-4c73-a54d-810bdd5e9f25.gif)

