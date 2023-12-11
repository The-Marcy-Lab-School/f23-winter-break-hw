# Winter Workshop Project Requirements

- [Winter Workshop Project Requirements](#winter-workshop-project-requirements)
    - [Make-up work](#make-up-work)
    - [How to Submit](#how-to-submit)
- [Projects](#projects)
    - [The Other Solo-Project-Week Project](#the-other-solo-project-week-project)
    - [Follow a Tutorial](#follow-a-tutorial)
    - [Create your own Project From Scratch](#create-your-own-project-from-scratch)
    - [Learn Python](#learn-python)
- [Tech Rubric](#tech-rubric)
- [Project Milesones](#project-milestones)


We hope that you have a restful break, but the truth is **it doesn't take long to forget how to code**! During your time off, you need to be coding weekly to keep your skills up. When we return, we will jump straight into Asynchronous JavaScript, which will rely on everything you just learned about the DOM, so there's no time for you to be rusty!

There are three different projects for this challenge, and we will work with you to select the one that's right for you! All three will be building a project with Vite, but the complexity will vary. We want you to take the break to **get comfortable with DOM and with putting together a multi-file project**. 

You've put so much effort into getting to where you are. Let's not take our foot off the pedal just yet!

## Make-up work
If you have any make-up work, you must use the break to complete it. We will be in touch about what past work we need to see completed over break. Make-up work should be completed before taking on a project.

## How to Submit
You will have to submit your GitHub repo link for this project. You should deploy these projects using GitHub pages if you can.

Here are some resources to help you get started and to deploy (which you can do from the start if you wish)!
* [Getting Started with a Vanilla JS Vite Project](https://github.com/The-Marcy-Lab-School/2-3-0-resource_getting-started-vite-vanilla-js/tree/main)
* [Deploying a Vite Project with Github Pages](https://github.com/The-Marcy-Lab-School/2-3-3-resource_deploying-with-github-pages)

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
- [Learn about Kaboom.js and make flappy bird!](https://www.youtube.com/watch?v=hgReGsh5xVU&ab_channel=Replit)
  - Same thing here for `localStorage`. Saving high scores should be a good option!
  - If you can, make this using Vite! 

## Create your own Project From Scratch

This is the most time-consuming project and is only recommended if you are already super comfortable with DOM Manipulation and localStorage. The requirements are exactly the same as our API project. If you aren't comfortable with DOM or `localStorage` yet, we do not recommend this option. Planning a project takes time, we want to be respectful of yours. You do not have to write a formal proposal and wait for approval — build what you want! However, we recommend you take some time to plan the project on your own, as that's extremely helpful.

But don't get carried away with the planning and complexity! Remember, the goal of the break project is to be familiar with DOM and comfortable putting together a multi-file project.

## Learn Python

And lastly, for those of you who are interested in participating in the JP Morgan Chase Super Day, you will need to know Python. You should only choose in this option if you are fully comfortable with DOM manipulation. 

Instead of building a project, you should complete the [Learn Python 3 course on Codecademy](https://www.codecademy.com/learn/learn-python-3).

Fellow taking on this path can skip the last two sections of this document.

# Tech Rubric
To see how well you're doing with this project, here are all the things we would like to see from you. As you can see, it is pretty open-ended!

**Layout: Structure**
- [ ] There is a single `main` element on the page
- [ ] There is a single `h1` element on the page
- [ ] There is a `title` in the `head`

**Layout: Accessibility**
- [ ] Forms have an `aria-label` or `aria-labelledby` attribute that describes the form
- [ ] Forms have `h2` labels
- [ ] Sections have an `aria-label` or `aria-labelledby` attribute that describes the section
- [ ] There are no instances of recreating any semantic elements (for example, don't use a `div` when a `nav` will do)

**Functionality**
- [ ] Data is stored in `localStorage`
- [ ] There is some degree of user event interaction

**Meta**
- [ ] The project is created using Vite
- [ ] The code exists in more than one JS file
- [ ] The project is deployed via GitHub Pages properly
- [ ] css flexbox or grid was used
- [ ] The code does not render unescaped text directly to the DOM (`createElement` or other escape method used)
- [ ] `.innerHTML` or the `createElement/.append` pattern is used properly at some point in the project

# Project Milestones

In Code Challenge, we use the PEDAC process to slow ourselves down and plan before diving straight in. The investment in planning upfront ends up saving us a lot of time and headaches down the line. The same is true when it comes to planning a project.

While each project is unique, there are common features of every project and we can break down a project into these milestones. Though the duration of each milestone will vary within each project, breaking down the project into these steps will help you stay on track.

Day 1 should be focused on planning and setup
Day 2 should be focused on 

### User Stories (Day 1)

A user story is a description of what the user can do using your application. For example:

> - A user can fill out a form to create a palette, selecting three colors, a temperature, and giving a title to their palette
> - A user can view all palettes that they have created
> - A user can delete a palette that they have created
> - A user can copy colors from a palette

User stories should be completed on the first day of planning and should take only an hour or so to complete. You can always return to add new user stories or remove/modify existing ones.

### Rough Sketch of the Application (Day 1)

You should have a _very_ rough idea of how the Minimum Viable Product (MVP) application will look. The key here is to know what key components the application will need at minimum:
* What are the major sections of your application?
* What static components will be there (navigation links, headers, etc...)
* Will it need a form? How many inputs? What kinds of inputs?
* What data will need to be displayed to the user?

Keep this low fidelity. You can draw this on a scrap piece of paper with a pencil if you like. Just boxes with some scribbled lines for text will do.

The key is envisioning what the application will look like with **little-to-no styling** so that you have something to work with at the start. Just like the user stories, you can always return to this to create a higher-fidelity design once the core features of your application have been built.

### Github Repo & Vite Setup (Day 1)

Once you know what your application will do and what visual components it will need, you can start setting up your project. 

* Create a repository on Github
* Clone it down and create a Vite Project inside. Here is a resource for [Getting Started with Vite](https://github.com/The-Marcy-Lab-School/2-3-0-resource_getting-started-vite-vanilla-js)
* Remove any unnecessary starter code
* Set up the basic HTML layout of your page. Focus only on the static HTML components (`main`, navigation, headers, major `section`s, any `form`s you need).

### Data Layer (Day 2)

Dedicate an entire day to figuring out your data. This step will require a fair bit of planning as well. You will want to answer these questions at minimum:

* What data will you provide when the application first loads (if any)?
* What data will the user generate?
* How will you structure that data?
* How will you store that data?
* How will that data be accessed?
* How will that data be modified?

Once these questions have been answered, you can begin building the API for your data storage. Create a separate file to handle all data-related functionality. Create and export your functions for creating data, reading (getting) data, updating data, and deleting data.

Make sure to test out your data storage API by importing those functions into a main file and see if all of the functions you created work as expected.

### Connect Data to User Interface (Day 3)

The goal here is to confirm that your data storage layer is connected to your user interface layer.

Use your DOM manipulation skills here to respond to user events, create new elements dynamically, and invoke your data storage API functions.

At minimum, the user should be able to create new data, insert that data in the data storage, and see existing data. 

Styling at this point is not important. We only need raw data rendered to the screen. 

### Styling and Deployment (Day 4)

Your data layer is working, your user interface can handle user interactions, and all of your core functionality is implemented. Now, it is time to style!

When designing your application...
* focus first on the layout (where will you use flex or grid?)
* then make your font and spacing choices (keep it consistent!)
* and finally, add color (keep it simple! Less is more. Choose a color palette and stick to it).

In addition to styling, remember to deploy your application so that the world can see it!

Use this [Deploying with Github Pages resource](https://github.com/The-Marcy-Lab-School/2-3-3-resource_deploying-with-github-pages) to help you out.

### Additional Features

Your project is basically working! Now it is time to return to the user stories, sketch, and data storage API, and add new features!
