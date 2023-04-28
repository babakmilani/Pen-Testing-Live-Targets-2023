# Pen-Testing-Live-Targets-2023
Pen Testing Live Targets Codepath Spring 2023


For this assignment, you will attack three live targets, each of which is a slightly modified version of the same web application, Globitek. The three targets are therefore mostly identical. However, each target has been given a different color menu bar—blue, green, red—and each one has two different security vulnerabilities.

Your challenge is to attempt to find and exploit the vulnerabilities. The goal is to identify which two vulnerabilities the blue target has, which two vulnerabilities the green target has, and which two vulnerabilities the red target has.

#GREEN
testing all three target's login page I noticed a difference in the Green Target Login page error message. After inspecting the page in firefox with a correct username / incorrect password, and incorrect username / incorrect password I saw a difference in the html class (failed/failure) in the source code. This leads me to believe there is a vulnerability there to be exploited.
![green_password_enumeration](https://user-images.githubusercontent.com/55906428/235255483-db0ef98a-1346-4170-86d2-b198e9ff5c01.gif)
