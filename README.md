# Name of project: BrainKwik (Working Title)

## Elevator pitch

BrainKwik is an online flash card creator that will help you memorize and study what you need fast. It is a well-designed, easy-to-use app that makes cramming for a test or remembering the names of members of your extended family easy. The initial scope of this app will focus on helping users build and study their own flash card sets. But it's also being built for scalability in which people can share and search for other flash card sets. (Not within the scope of this class.)

## Expected dependencies

* React router
* Bootstap
* Firebase

## Tasks

* Architect underlying database in firebase. Should be organized by User > Flash Card Set > Card
  - Metadata for each flashcard set (Title, Times Practiced, Category, Shared with public (boolean), Last Practiced)
  - Metadata for each card (Side A, Side B, Number of times answered, Number of times correct)
* Set rules for database
* Start create-react-app scaffold
* Create login screen route for app
  - Minimum Google and by email
* Build preset flash card sets in Firebase available to all users
* Create UI for flash card building screen (requires route)
  - Implement form validations and checks
  - Minimum set should have a category, a title and at least one complete card.
  - Store this information in state and send back to firebase on completion
* Connect flash card builder to firebase database
 - Fetch card set from firebase and store in state
* Create UI for flash card answering
 - Store performance in state. Send performance to firebase on completion

Reach goals:
* Allow users to track how well they've been doing in each set.
* Allow users to customize study sessions (number of cards, only cards below a certain success rate, etc.)
* Allow users to share their sets with other users.

## Wireframes

See images in repository

## Plan and timeline

May 29 - May 31
* Architect underlying database in firebase. Should be organized by User > Flash Card Set > Card
  - Metadata for each flashcard set (Title, Times Practiced, Category, Shared with public (boolean), Last Practiced)
  - Metadata for each card (Side A, Side B, Number of times answered, Number of times correct)
* Set rules for database
* Start create-react-app scaffold
* Create login screen route for app
  - Minimum Google and by email
* Build preset flash card sets in Firebase available to all users

June 1-June 5
* Build preset flash card sets in Firebase available to all users
* Create UI for flash card building screen (requires route)
  - Implement form validations and checks
  - Minimum set should have a category, a title and at least one complete card.
  - Store this information in state and send back to firebase on completion
* User test the flash card building
  
June 6-9
* Connect flash card builder to firebase database
 - Fetch card set from firebase and store in state
* Create UI for flash card answering
 - Store performance in state. Send performance to firebase on completion
* User test the flash card answering

June 10-14
* Polish and bug removal

June 15
* Submit project
 
---------

# Week 7 Assignment

Your assignment for this week is to think of a final project idea and create a plan for the project.

## Final Project Requirements

* The project must be a React application, bootstrapped with `create-react-app`
* Your app must be created and visible in a Github repo under your Github account
* Your app must be your own work. You may have a partner if you'd like, but be aware that you'll need to come up with a strategy for working together. Most developers on small projects create branches for new features/fixes, then merge them back into the `master` branch. Merge conflicts can arise, and you'll need to know how to resolve them.
  * The simplest and most straightforward workflow for each team member:
    ```bash
    # create a branch off of master
    git checkout master
    git branch -b feat/new-feature-name

    # commit code to this branch
    git add .
    git commit -m 'more code'

    # periodically push to Github
    git push
    ```
  * Create pull requests on Github into the `master` branch when ready to merge code. It's recommended that you merge only working and/or tested code.
* Your app should be deployed onto a web server and publicly accessible (unless you decide to use React Native. In that case, it's recommended you use [Expo](https://expo.io/) to share the project).
* Your app should be polished. Some recommendations for this requirement:
  * Remove `console.log` statements once you're finished with development
  * Utilize CSS and images to make your app look great
  * Check for any React errors in the console
  * Perform some basic user testing. Have other people use your app and receive feedback on usability
  * Keep your feature set small, so you'll have time to polish the app
  * Write tests
* If you're feeling adventurous, you can also use React to build mobile apps using the [React Native](https://reactnative.dev/) framework. Usage is allowed for this project, **but** note that it will involve additional learning and research. Proceed at your own risk.

Other than the above requirements, you're encouraged to be creative and create something you're proud of. It can be as simple or as complex as you want, and it should be high quality.

## Assignment Requirements

Above are the requirements for the project. For this week however, you'll need to create a plan for your project. More details are to come, but you'll need to create a pull request with the following:

* The name of your project
* An elevator pitch (a paragraph about what your project does). Be sure to address:
  * Who will use your project
  * The value that your project will provide to the end user
* [Wireframes](https://en.wikipedia.org/wiki/Website_wireframe) to help visualize what your project will look like
  * These wireframes do not have to be high-fidelity. You're free to use boxes, hand drawings, tools such as Draw.io, etc.
* A list of dependencies you'll be using for your project (npm modules, APIs, Firebase, etc.)
  * This list will likely change as you work on your project, but listing your dependencies will help you visualize the complexity of the project
* A list of tasks that need to be completed for your project
  * Example list of tasks for the Star Wars films example:
    * Setup `create-react-app` scaffold
    * Call the Star Wars API and print results
    * Store API results in React component state
    * Render React state
* A plan for the next 3 weeks and what you plan to accomplish each week

## Recommendations

* Keep the scope of your project small. A small, completed project is much better than a large, incomplete project. You can create a list of "nice to have" features that you can work on if you have time (similar to how our assignments have a main list of requirements and "bonus" items).
* Ensure you have plenty of buffer time in your schedule. Life events pop up, and tasks can take longer than initially estimated.

## Submitting your Project Idea

1. Fork this repository
2. Add your project name, elevator pitch, wireframes, dependencies, task list, and plan to the Github repo (you can add a markdown file + images or links to images)
3. Create a pull request
