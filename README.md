# 09 Node.js Challenge: Professional README Generator

## Description
I was motivated to develop a dynamic README file that could be customized based on user inputs. The primary objective behind building this project was to simplify the process of generating a README file by utilizing predefined parameters. The issue I resolved was the time-consuming task of manually creating a README file, which was overcome by implementing a set of easily integrated questions that automatically generate the file. Throughout this project, I acquired valuable knowledge in utilizing JavaScript alongside Node.js.

## Installation: 
Clone the remote repository or zip the file to your local respository.  
Then the application will be invoked by using the following command in the terminal:

```bash
node index.js
```
## Screenshots 
![Screenshot of terminal](media/READMEgenerator1.jpg)


![Screenshot of completed READMe file Generated](media/READMEgenerator2.jpg)

## Video
https://youtu.be/8oGWJOKyoh4

## Github Repository 
https://github.com/karafaris/READMEgenerator.git

## User Story

```md
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project
```

## Acceptance Criteria

```md
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

