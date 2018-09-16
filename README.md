# React Redux How-To

A quick guide on how to get started with React-Redux from
the ground up.
This guide will get you to the point where the React-Redux
demo will take over (they did a good job writing it)
and follow up with styling and next steps

This guide also tries to provide a general orientation
towards working with Node, JavaScript, and a showcase of my
dev environment.

Getting Started
---------------

#### Downloads

- NodeJS - engine that runs JavaScript, so basically everything here, as well as manages packages so you can download even more crap
- Git - manages version control
- Atom (or other text editor) - I prefer atom because it's open source, extendable, has git integration (Atom is made by the people at github), and personal learning of shortcuts. Use whatever you want but I like Atom for those reasons

#### Create React App

[Create React App](https://github.com/facebook/create-react-app)
 is a popular boilerplate framework for React apps.
 It includes a carefully chosen series of other packages and
 wraps it all in a simple script (a boilerplate's job kinda).

 Follow the instructions in the link to create your app.
 As mentioned in their README, the `npx` command is included
 with `npm`, which ships with NodeJS. This is the only time
 I've ever seen `npx` used and later I'll talk about `npm`
 and how cool it is.

 Create React App takes a moment to do it's thing. Don't be
 alarmed

 #### Intro to React

 When create-react-app is done, you'll have your first react
 app. Run it, see that it works, then look a bit into how it
 works.

 React is a very popular and powerful framework for making
 web applications that are responsive and UI driven.

 One of the things React does is allow you to define, manage,
 and do actions with custom components. In vanilla HTML, your
 content goes into a series of pre-defined components, like
 the paragraph tag or assorted `<div>` tags. React build a
 way for your to display content in custom defined tags, like
 a `<TodoListItem />` tag. You're given the ability to write
 these tags and manage their properties, the inner HTML to
 display them, their styles, and custom code when a user
 interacts with them.

 create-react-app makes a React Native application for you to
 play around with. The App component is found in App.js in
 the src directory

 #### Redux
 [Redux](https://redux.js.org/) is a framework/technique for defining a UI, the actions
 a user can perform, how the UI responds to them, and how the
 UI is physically displayed. It's more of a style of programming than a specific implementation, and can be used
 in almost any framework, including vanilla JavaScript on a
 webpage. Redux is very popular when working with React, since
 they both use a state based model for understanding the UI
 and other things that make them play nice together.

 Redux has a wonderful tutorial for how to make a simple
 react-redux application. It's amazing and a great intro to
 how react works in general and how awesome programming in
 it can be.

 [Here's their guide to learning the basics for Redux in React](https://redux.js.org/basics).
 The first few pages remain fairly framework agnostic while
 the meat and potatoes are explained, and the last
 few pages talk about specific parts of React. Follow at your
 own pace. I prefer to get an overview of everything before I
 start coding, but they have the guide set up for you to code
 along (all the code needed for the app is on the last page
 too).

One last thing before I turn you over: `npm`.
NPM (Node Package Manager) is a command you get with NodeJS
to help you manage an assortment of node packages, their
dependencies, and other cool stuff. As alluded with the
boilerplate for create-react-app, you can just type
`npm start` to launch your app, and npm was told that start
means to call a more verbose command (check it out in
 package.json)

 The next most common use of npm is installing new packages.
 For react-redux, you'll need to install react-redux which is
 done as follows:

 ```
 npm i --save react-redux
 ```

 The order of those commands is kinda fluid but here's how
 it boils down.
 - npm - base command
 - i - install (you could just type install instead, they're considered equal)
 - --save - save the package you're downloading to package.json. This tracks the version and lets others download the package too, so PLEASE USE
 - react-redux - Name of the package. If you want to download multiple, you can keep adding package names

 Anyway, that's the fundamentals you'll need going into
 the React-Redux tutorial. If you have any questions, the
 internet is often your best guide, but I'll be happy
 to answer
