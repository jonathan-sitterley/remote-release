# Remote Release Project
## Description

The purpose of this project is to create the following

- A remote control that can transmit commands via bluetooth
- A microcontroller that can receive commands via bluetooth and relay to peripherals
- A mechanical release that can hold and release a load up to 5 lbs

## Table of Contents

- [Developer Tools](#developer-tools)
- [Cloning Instructions](#cloning-and-setup)
- [How the Project was Built](#build-history)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Testing](#tests)

## Developer Tools

- Task Management: Trello
- IDE: Visual Studio Code
- Arduino IDE
- Version Control: Git
- Repository: Github

## Cloning and Setup

Follow the steps below to clone the respository
1. Clone the repository from Github
    - 

## Build History

The steps below were taken to manage this project and reach the hello world state:
1. Create Trello Board to build out project plan
2. Setup GIT for version control
    - Create .gitignore file in base directory
    - Install Git on developer system from https://git-scm.com/ (follow installation instructions)
    - From command prompt, navigate to mean directory, then execute "git init"
3. Setup Github Repository to store project files
    - Install Github CLI
    - Create Github account (if one does not exist)
    - Create a repository on github to store project
    - Authenticate Github on developer system (a token will need setup)
        - Navigate to the project directory and execute "gh auth login --hostname https://github.com/"
    - Link to new repository by executing: git remote add origin https://github.com//.git
        - Note: Once git is configured, it will also work within Visual Studio; User may update via CLI or IDE
    - Push procedure from project directory:
        - Add all files (excluding gitignore items), execute "git add -A"
        - Commit files, execute "git commit -m "(Add a message to describe commit here)"
        - Push git commit to Github "git push -u origin master"

## Usage

1. Complete all of the installation and setup steps
2. 

## Credits

Resources used to build this project:
- https://docs.arduino.cc/
- Git CLI: https://cli.github.com/manual/

## License

MIT License

Copyright (c) 2023 Jonathan Sitterley

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

---

## Tests

To test this project, run through all of the cloning instructions and validate that the program executes properly