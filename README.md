# Progressive Web Applications (PWA) Challenge: Text Editor
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)]

# Table of Contents 

[User Story](#User-Story)

[Usage](#Usage)

[Instlation](#Instalation)

[Links](#Links)

[Visuals](#visuals)

[Contributing](#contributing)

[Questions](#questions)

[Acceptance Criteria](#acceptance-criteria)


## User Story 
* AS A developer
* I WANT to create notes or code snippets with or without an internet connection
* SO THAT I can reliably retrieve them for later use

## Usage 
This project features impressive expressions and concepts from our lessons. This project is building a  text editor that runs in the browser. This app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline. It uses a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

## Instalation 
`npm i` with concurrently will install on the client and server ends, then `npm run start:dev` to run in develop mode. 
 
## Links
deployed 
walk through video   

## Visuals 
[Screenshot of Offline site in `npm run start:dev`](./photos/Screenshot%202023-04-27%20092036.jpg)

## Contributing 
This text editor was built with an existing, "starter code" application. This assignment was worked on by student, M.C. Wambaugh, with the support of her TA's during office hours and meeting regularly with a tutor, and her classrom peers. The student also used universial resources such as  YouTube.com, shields.io/, and our class repo examples. Many thanks to those who continue to support learning in the technological community.

## Questions 
Please direct questions to Marta Wambaugh at marwambaugh@gmail.com and https://github.com/mwambaugh 

## Acceptance Criteria 
* GIVEN a text editor web application
* WHEN I open my application in my editor
* THEN I should see a client server folder structure
* WHEN I run `npm run start` from the root directory
* THEN I find that my application should start up the backend and serve the client
* WHEN I run the text editor application from my terminal
* THEN I find that my JavaScript files have been bundled using webpack
* WHEN I run my webpack plugins
* THEN I find that I have a generated HTML file, service worker, and a manifest file
* WHEN I use next-gen JavaScript in my application
* THEN I find that the text editor still functions in the browser without errors
* WHEN I open the text editor
* THEN I find that IndexedDB has immediately created a database storage
* WHEN I enter content and subsequently click off of the DOM window
* THEN I find that the content in the text editor has been saved with IndexedDB
* WHEN I reopen the text editor after closing it
* THEN I find that the content in the text editor has been retrieved from our IndexedDB
* WHEN I click on the Install button
* THEN I download my web application as an icon on my desktop
* WHEN I load my web application
* THEN I should have a registered service worker using workbox
* WHEN I register a service worker
* THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
* WHEN I deploy to Heroku
* THEN I should have proper build scripts for a webpack application
