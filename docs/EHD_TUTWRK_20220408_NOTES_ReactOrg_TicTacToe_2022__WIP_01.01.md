<style>
.ehw-bq__tip {
  background: #ffffb3;
  border-left: solid 4px orange;
  min-height: 20px;
  padding: 1rem 2rem;
  margin: 1rem;
}

.ehw-bq__tip h3 {
    color: brown;
    font-weight: bold;
    margin: 0;
}
</style>


# TUTORIAL NOTES

### <span style="background:#831900;color:white; padding: 1.8em; padding-top: .1em; padding-bottom:.2em; ;border-radius:10px">Tutorial: Intro to React (Tic-Tac-Toe Game)</span>

## TUTORIAL INFO

| Title:          | Modern JavaScript From The Beginning                            |
| --------------- | --------------------------------------------------------------- |
| URL:            | <https://reactjs.org/tutorial/tutorial.html>                    |
| Platform:       | Website                                                         |
| Channel:        | **ReactJs.org**                                                 |
| Instructor:     | N/A                                                             |
| Release Date:   | UNKNOWN                                                         |
| Date Started:   | 04/08/22                                                        |
| Last Modified:  | --                                                              |
| Date Completed: | ***--***                                                        |
| File Name:      | EHD_TUTWRK_20220408_NOTES_ReactOrg_TicTacToe_2022__WIP_01.01.md |

### What you'll learn

We will build a small game during this tutorial. You might be tempted to skip it because you’re not building games — but give it a chance. The techniques you’ll learn in the tutorial are fundamental to building any React app, and mastering it will give you a deep understanding of React.

<blockquote class="ehw-bq__tip">
<h3>Tip</h3>

This tutorial is designed for people who prefer to learn by doing. If you prefer learning concepts from the ground up, check out our step-by-step guide. You might find this tutorial and the guide complementary to each other.
</blockquote>

---

### The tutorial is divided into several sections:

- Setup for the Tutorial will give you a starting point to follow the tutorial.
- Overview will teach you the fundamentals of React: components, props, and state.
- Completing the Game will teach you the most common techniques in React development.
- Adding Time Travel will give you a deeper insight into the unique strengths of React.

You don’t have to complete all of the sections at once to get the value out of this tutorial. Try to get as far as you can — even if it’s one or two sections.

---

### What Are We Building?

In this tutorial, we’ll show how to build an interactive tic-tac-toe game with React.

You can see what we’ll be building here: Final Result. If the code doesn’t make sense to you, or if you are unfamiliar with the code’s syntax, don’t worry! The goal of this tutorial is to help you understand React and its syntax.

We recommend that you check out the tic-tac-toe game before continuing with the tutorial. One of the features that you’ll notice is that there is a numbered list to the right of the game’s board. This list gives you a history of all of the moves that have occurred in the game, and it is updated as the game progresses.

You can close the tic-tac-toe game once you’re familiar with it. We’ll be starting from a simpler template in this tutorial. Our next step is to set you up so that you can start building the game.

### Prerequisites

We’ll assume that you have some familiarity with HTML and JavaScript, but you should be able to follow along even if you’re coming from a different programming language. We’ll also assume that you’re familiar with programming concepts like functions, objects, arrays, and to a lesser extent, classes.

If you need to review JavaScript, we recommend reading this guide. Note that we’re also using some features from ES6 — a recent version of JavaScript. In this tutorial, we’re using arrow functions, classes, let, and const statements. You can use the Babel REPL to check what ES6 code compiles to.


---


## NOTES

### [Create React App](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app)

Create React App is a comfortable environment for learning React, and is the best way to start building a new single-page application in React.

It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. You’ll need to have Node >= 14.0.0 and npm >= 5.6 on your machine. To create a project, run:

~~~bash
npx create-react-app my-app
cd my-app
npm start
~~~