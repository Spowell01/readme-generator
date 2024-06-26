# Profesional README Generator

## Description
A user can use this application to generate a professional README that can be modified after it is generated. The user will use node index.js and answer the questions that appear on the command line. 


# Overview
## The Challenge:
Create an effective command-line runned application that in-takes a users input inorder to dynamically generate a professional README.md file that will have a clean, minimal and visually appealing format.

## User Story
```
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional 
README for a new project
```

## Acceptance Criteria
```
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
```

## Usage Instructions
1. Open the cloned repository in a source code editor e.g. Visual Studio Code.
2. Open integrated terminal on index.js
3. Enter “node index.js” in the command line
4. Presented with npm inquirer questions through sequential order within the directory -  the user must provide essential README information in order to proceed to the next question in sequence.
5. Once completed a file named (Generated)README.md will be made.
6. At your discretion, you may rename the (Generated)README.md file to the file name of your choice.
7. (Optional) Regarding future use, you may alter the prompted questions within the index.js and generatedMarkdown.js to suit your needs.
8. (Optional) The (Generated)README.md file serves as a foundation so you are not limited to altering the file - once generated you may alter the document to your preferences just like any other README.md file.

## Installation Process
1. Clone the repository
2. Install Node.JS
3. Open the cloned repository in a source code editor.
4. Open integrated terminal on index.js in order to run "npm i" on the command line to ensure that "node-modules" and "package.json" are operating on your local device.

## Built With
- JavaScript
- Node.js
- Inquirer.js
- License Badge
- Visual Studio Code
- Professional Guide

## Credits

- I watched several youtube videos to understand node.js better.
- I used https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide to gain better - - - - understanding on what goes into a professional README document.
- I also referenced the mini project to understand how to format the template all of the information that is inputted by a user.
- Source code came from https://git.bootcampcontent.com/Ohio-State-University/OSU-VIRT-FSF-PT-01-2024-U-LOLC/-/tree/main/09-NodeJS/02-Challenge?ref_type=heads

## License
MIT License

Copyright (c) 2024 Storm Powell

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.