# l37b-todo-redux

* [submission PR](https://github.com/401-advanced-javascript-kimball/l37b-todo-redux/pull/1)
* [travis](https://travis-ci.com/401-advanced-javascript-kimball/l37b-todo-redux)

# LAB - 

## Project Name

### Author: Student/Group Name

### Links and Resources
* [submission PR](http://xyz.com)
* [travis](http://xyz.com)
* [back-end](http://xyz.com) (when applicable)
* [front-end](http://xyz.com) (when applicable)

#### Documentation
* [api docs](http://xyz.com) (API servers)
* [jsdoc](http://xyz.com) (Server assignments)
* [styleguide](http://xyz.com) (React assignments)

### Modules
#### `modulename.js`
##### Exported Values and Methods

###### `foo(thing) -> string`
Usage Notes or examples

###### `bar(array) -> array`
Usage Notes or examples

### Setup
#### `.env` requirements
* `PORT` - Port Number
* `MONGODB_URI` - URL to the running mongo instance/db

#### Running the app
* `npm start`
* Endpoint: `/foo/bar/`
  * Returns a JSON object with abc in it.
* Endpoint: `/bing/zing/`
  * Returns a JSON object with xyz in it.
  
#### Tests
* How do you run tests?
* What assertions were made?
* What assertions need to be / should be made?

#### UML
Link to an image of the UML for your application and response to events

----------

# LAB - Dynamic Forms

Wire dynamic forms into your To Do application, replacing standard state and/or a Form Hook.

## Before you begin
Refer to *Getting Started*  in the [lab submission instructions](../../../reference/submission-instructions/labs/README.md) for complete setup, configuration, deployment, and submission instructions.

## Getting Started

Starter code has been provided for you in the `/lab/starter-code` folder. 

Open [Code Sandbox](http://codesandbox.io) and Create a new application. When prompted, choose "From GitHub" and then paste in the URL to today's starter code folder from your fork of the class repository.

You will be submitting the URL to this working sandbox as part of your assignment.

## Practice - Wire up forms
You have been provided, in the `starter-code/practice` folder, a working application using standard React forms with some hooks that deal with the form submission

**Task 1: Refactor to use Redux Forms**
* Copy the `player-form.js` into a new file called `player-redux-form.js` 
* Alter the `player.js` file to import this file as a new component called `PlayerFormRedux`
* Render the PlayerFormRedux component in addition to the `PlayerForm`
* Don't forget to wire `redux-form` into your store

**Task 2: Refactor to use JSON Schema Form**
* Copy the `player-form.js` into a new file called `player-json-form.js` 
* Alter the `player.js` file to import this file as a new component called `PlayerFormJSON`
* Render the PlayerFormJSON component in addition to the other 2
  * Don't forget to import the schema.json file
  
**How do you know when you're done?**

Your application should show 3 player forms below the list of players. You should be able to click the edit button and see a player in each of the forms. Editing and saving one should reflect in all 3 if you have this all wired up correctly.
  
**Stretch Goal**
* Copy the player form again
* Find an alternative react/redux form library
* Wire it up

For the README on this practice assignment, provide a report detailing the pros, cons, gotchas, other comparisons along with your general and implementation details for each approach.


## To Do App Assignment
**Refactor the To Do application to use Redux and a form library**

You'll be given a working To Do application which you must refactor as follows:
 
**State Management**
* Convert the state management to a Redux Store.
* Create a Redux Store, a To Do store/reducer/action set
* Wire up the components to subscribe to the store for state and actions

**Form Handling** 

Convert ths current form rendering/submission process into one of either

* React JSON Schema Form
* Redux Form
* A form library of your own choosing


> If you choose to use JSON Schema Form, begin by replacing the schema.json file with one suitable for the to do application

> This will come from the `/api/vi/todo/schema` route in either your deployed API or the official one.


  
### Assignemnt Submission Instructions
Refer to the the [lab submission instructions](../../../reference/submission-instructions/labs/README.md) for the complete lab submission process and expectations

----------

