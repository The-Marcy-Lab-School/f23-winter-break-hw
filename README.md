# Winter Workshop Project Requirements

- [Winter Workshop Project Requirements](#winter-workshop-project-requirements)
- [How to Submit](#how-to-submit)
- [Projects](#projects)
  - [The Other Solo-Project-Week Project](#the-other-solo-project-week-project)
  - [Follow a Tutorial](#follow-a-tutorial)
  - [Create your own Project From Scratch](#create-your-own-project-from-scratch)
- [Make-up work](#make-up-work)

We hope that you have a restful break, but the truth is **it doesn't take long to forget how to code**! During your time off, you need to be coding weekly to keep your skills up. When we return, we will jump straight into Asynchronous JavaScript, which will rely on everything you just learned about the DOM, so there's no time for you to be rusty!

There are three different projects for this challenge, and we will work with you to select the one that's right for you! All three will be building a project with Vite, but the complexity will vary. We want you to take the break to **get comfortable with DOM and with putting together a multi-file project**. 

You've put so much effort into getting to where you are. Let's not take our foot off the pedal just yet!

# How to Submit
You will have to submit your GitHub repo link for this project. You should deploy these projects using GitHub pages if you can.

Here are some resources to help you get started and to deploy (which you can do from the start if you wish)!
* [Getting Started with a Vanilla JS Vite Project](https://github.com/The-Marcy-Lab-School/2-3-0-resource_getting-started-vite-vanilla-js/tree/main)
* [Deploying a Vite Project with Github Pages](https://github.com/The-Marcy-Lab-School/2-3-3-resource_deploying-with-github-pages)

# Make-up work
If you have any make-up work, you must use the break to complete it. We will be in touch about what past work we need to see completed over break. Make-up work should be completed before taking on a project.

# Projects

## The Other Solo-Project-Week Project

This option is pretty straightforward. If you enjoyed building one of these solo-project-week projects, then give the other one a go! Each project has interesting challenges, yet much of the code you wrote for the first project will be useful in the second project. 

- [Palette Picker](https://github.com/The-Marcy-Lab-School/2-3-0-solo-project_palette-picker)
- [Compare Movies with Chart.js](https://github.com/The-Marcy-Lab-School/2-3-0-solo-project_compare-movies)

## Follow a Tutorial

- [Ben's Todo App](https://github.com/benspector-mls/f23-2-3-0-todo-app-example)
  - This project is perfect if you found the solo project week projects were too challenging. This project walks through step-by-step instructions on how to build a to-do list using many of the same techniques needed to build the solo-project-week project.
- [Build the Chrome Dinosaur Runner Game](https://www.youtube.com/watch?v=lgck-txzp9o&t=1295s&ab_channel=KennyYipCoding)
  - For this one, you'll need to find a way to incorporate `localStorage`. How about saving the user's high scores?
  - Try to make this one using Vite!
- [Build Tic Tac Toe](https://www.youtube.com/watch?v=sNn_Gxph3TY&ab_channel=CodinginPublic)
  - Same thing here for `localStorage`. Maybe save the game state so you can leave a game mid-game and return to it?
  - Try to make this one using Vite!

## Create your own Project From Scratch

This is the most time-consuming project and is only recommended if you are already super comfortable with DOM Manipulation and localStorage. The requirements are exactly the same as our API project. If you aren't comfortable with DOM or `localStorage` yet, we do not recommend this option. Planning a project takes time, we want to be respectful of yours. You do not have to write a formal proposal and wait for approval — build what you want! However, we recommend you take some time to plan the project on your own, as that's extremely helpful.

But don't get carried away with the planning and complexity! Remember, the goal of the break project is to be familiar with DOM and comfortable putting together a multi-file project.

# Tech Rubric
To see how well you're doing with this project, here are all the things we would like to see from you. As you can see, it is pretty open-ended!

## Layout: Structure
- [ ] There is a single `main` element on the page
- [ ] There is a single `h1` element on the page
- [ ] There is a `title` in the `head`

## layout: Accessibility
- [ ] Forms have an `aria-label` or `aria-labelledby` attribute that describes the form
- [ ] Forms have `h2` labels
- [ ] Sections have an `aria-label` or `aria-labelledby` attribute that describes the section
- [ ] There are no instances of recreating any semantic elements (for example, don't use a `div` when a `nav` will do)

## Functionality
- [ ] Data is stored in `localStorage`
- [ ] There is some degree of user event interaction

## Meta
- [ ] The project is created using Vite
- [ ] The code exists in more than one JS file
- [ ] The project is deployed via GitHub Pages properly
- [ ] css flexbox or grid was used
- [ ] The code does not render unescaped text directly to the DOM (`createElement` or other escape method used)
- [ ] `.innerHTML` or the `createElement/.append` pattern is used properly at some point in the project
