# Code In The Dark Challenge
> **Code in the Dark** is a thrilling competition
> where you get the chance to put your mad HTML and CSS skills to the ultimate test.
> Contestants try to recreate an image with only HTML and CSS (and possible vanilla JavaScript) without previewing it.
> Then the public/experts decides who wins.

This repository provides ready-to-start template.

## For Contestants
Open `task.png` image.
Try to recreate this image using your HTML + CSS + JavaScript skills.

You must follow only to 2 rules:
- Do not open browser to see served preview of your application!
- Do not use any files except `index.{html,css,js}` or `task.png`!

> Of course, using `<img src="task.png">` is not allowed solution :D

## For Organizator

### Prerequisites
- Install [Node.js](https://nodejs.org) LTS
- Install any modern browser ([Google Chrome](https://www.google.com/chrome) is recommended)
- Install [Visual Studio Code](https://code.visualstudio.com)
- Create your own repo from this template using **any** of this approach:
  * [Create from template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template)
  * [Fork this repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#forking-a-repository)
  * Classic `Ctrl` + `C` and `Ctrl` + `V`
- Open the repository inside Visual Studio Code

### Getting Started
Both approaches support Hot Module Replacement for HTML / CSS / JS files.

> Hot Module Replacement allows you to update your code without having to refresh the page,
> such as editing `index.html` / `index.css` / `index.js`,
> the changes are immediately reflected in the browser.
> 
> It provides your spectators an opportunity to watch always up-to-date preview of contestants' code.

#### Approach 1 - Via Visual Studio Code Extension
1. After opening cloned repo in Visual Studio Code,
   it will suggest (at the bottom-right part of the window)
   to install recommended for this project extensions. Agree to it.
2. Open `index.html` and make right-click on any part of this file.
3. Select option "_Open with Live Server_"

#### Approach 2 - Via Vite
1. Run the following command from the root of the project
   ```
   npm ci
   ```
2. Run application
   ```
   npm start
   ```
