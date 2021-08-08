# Netflix-Clone-in-PEGA
The Code for Netflix Clone has been Given.  kindly use it and don't forget to Fork it
PEGA (Angular Dev's first React project) - Netflix clone

I am an angular collaborator and an avid user of Angular this is my first react project a Netflix clone in PEGA using react, styled components, jest tests. It uses firebase firestore as the DB if you want to run it you have to set it up using the seed data already given. To setup follow the instruction in readme and firebase.prod.js. You can also fork my repo or set it upto learn more.
Few of my positive experiences
Creating a component in React.js is a dream components cannot be created easier than this.
Hooks for state management - Hooks are a really easy paradigm for state management

Neutral experiences
Styled components - Suffers from scalability problems writing styles again and again seemed weird but the scoping was great.

Negative experiences
Context was weird Calling use context again and again seemed odd somehow. Maybe I'm not accustomed to it.
How to find right tools for the job you are trying to do. React has so many options which is great but it makes choosing the right tool that much harder.
How to scale react could not find good resources on it.

Angular apparent short comings after using React
State Management- It has nothing compared to hooks
Component creation is so hard in Angular
Why do we need modules. Why?
Angular team giving every package has taken its toll on angular innovation. Not much is tried by the community in angular.

Angular strong suit
Angular basics will always be same because of the same lib use so easy to work on multiple projects
Angular directives there is nothing like them
Angular schematics setting up libs for you is great
Angular Cli is the best

CSS Management
I don't know how we got to this place in frontend but there is no great way in Angular or react to manage your CSS is important in frontend but not much attention or tooling is there for managing it
Let me know in the comments if I'm wrong about something or I need to study more I'm trying to learn other frameworks so that I know more paradigms in frontend development.

This is an sample video how Netflix Clone has been built on PEGA . I have already added code in my GitHub repo, now I would teach ,the way it has been implemented and done .
Create a Ruleset unauthenticated (Records -> Sysadmin -> Ruleset) and it to your application definition.

2. Create an Access group Unauthenticated and enter the name and version of the current application.
3. Select the portal as pyCasemanager7 and available roles as PEGA:Guest.
4. In the advanced tab, under work pool add PegaSample.
5. In the advanced tab, under Runtime Configuration add the created ruleset in the Production Ruleset.
6. Create a binary file ( Create -> Technical -> Binary file) to add the background image.
7. In the search box at the top right corner, search for web-login and open it.8. Save as the web-login into the new created ruleset (Unautenticated).
8.In the web-login fork my Netflix Clone code and paste it , and save it.
9.Kindly use PEGA O-AUTH Feature for Login Purpose and kindly add the Required JS File and CSS file to your PEGA REPOSITORY.
10. Go to Records -> Sysadmin -> RequestorType.
11. Click on Pega Browser and add Unauthenticated ruleset.
12. Logout to view the NETFLIX CLONE on your WEB-Login.
