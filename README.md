# Pen-Testing-Live-Targets-2023
Pen Testing Live Targets Codepath Spring 2023


## GREEN
CROSS-SITE SCRITPING(XSS):
inject a simple XSS line of code on the page with the form. Once user logins in a popup alert box will appear with 
the message. 

![green_XSS](https://user-images.githubusercontent.com/55906428/235280733-0b19150f-5912-4609-a11e-f105aa4a2e6b.gif)


PASSWORD ENUMERATION:
theres a difference in the message after a login attempt which indicates theres a vulnerability which can
foretell which username is correct and which one is not.

![green_password_enumeration](https://user-images.githubusercontent.com/55906428/235281013-778904f2-c9aa-45fc-8ca4-eeb375bd9739.gif)

## BLUE
SQLi : inject a sql instead of a the Salesperson' ID Number revealed a lag in response so that indicates
there is a vulnerability in the code to access the Database.

![blue_SQLi](https://user-images.githubusercontent.com/55906428/235257713-da306cda-09f3-4c47-91f1-041b93e5f3fd.gif)


## RED
IDOR : revealing restricted user accounts. 
Hidden accounts are displayed by simple iteration in the URL parameter section.

![red_IDOR](https://user-images.githubusercontent.com/55906428/235280122-986b0ec1-8c2a-4c73-a54d-810bdd5e9f25.gif)

