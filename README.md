# NodeJS

## Introduction:

A blog site covering the basic concepts of NodeJS.

## Pre-requisites:

- NodeJS (https://nodejs.org/en/)

## Stack (Tools and Technologies):

- Technologies:
  - <b>NodeJS</b> - Main Framework
- Tools:
  - <b>VS Code</b> - IDE
  - <b>GitBash</b> - Version Control
  - <b>Chrome</b> - Web Browser (others can also be used like Chrome, Safari, Firefox)

Setup:
------

  First, verify if your machine has the node installed by running the command `node -v` in a teminal. If you get to see a version, that means node is installed, otherwise, visit the [official page](https://nodejs.org/en/) of node to install the latest version of node js. After doing so, verify again following the same method.

  Once the node is installed, you can use it in a terminal by using the command `node` and start to code in JS.

  Alternatively, we can create a js file, and run it by using the command `node <path/to/file>`

</br>

# Basic Concepts

## Intro
  JS has been `confined to run in the browser` for a long and used for FE and add interactivity. `Node allows JS to run on the machine or server`.

  Computer understands machine language which is in bits. On top of that, a simpler language i.e. assembly language is used. Then we have programming langs like C++ which then compiles to assembly and so on.

  JS is more higher level language so the computer doesnt understands it. It can run `inside a browser`. Inside browser, an engine called `V8` runs, which is written in `c++ by google` which compiles JS to machine code in runtime. So the computer understands the JS inside the context of browser.

  To run JS `outside a browser`, NodeJS comes into play. V8 engine also lives in node. NodeJS is also written in `C++` that is why it can run on `computer or a server`. After installing node js, it can take JS, it runs it through the V8 engine/compiler and compiles the JS in machine language.

  Apart from being a wrapper to V8 engine, node also hooks into V8 engine to add more funcionality to JS. Things like `read/write a file` on a computer, `connection to a DB` or act as a `server for content`.

  Since we are using the JS `outside the browser` now, we `lose access` to JS features like `DOM`, we cant `interact with HTML` but we dont need it cuz we are using it as a BE server.

  ### Flow
  
  We'll use node to `handle the requests` from a browser or a client. The flow would be somewhat like: a `request comes from the browser`, `Node accepts` it and `fetches data from DB/files` and `formulates a response`. That response could be an HTML page with dynamic data embedded or with some CSS or image data etc.

  ### Advantages over other BE languages:

  - No need to learn extra language for BE
  - Can share code for BE and FE
  - Massive community
  - Huge amount of 3rd party packages

## Create a server using Node.js

## Create an express app / website

## Read and Write files on computer

## Use MongoDB (a NoSQL DB)

## Use template engines to easily create HTML VIews
