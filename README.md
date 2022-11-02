# Tic Tac Toe
This is a recreation of Tic Tac Toe in vanilla JavaScript

## Why recreation?
After working through some DSA topics (linked lists, trees, tree traversals, graphs), I 
wanted to recreate a Tic Tac Toe game with an implementation of the minimax algorithm.
Also I wanted to get more practice with Webpack, ESlint and testing.

## Setting it all up
After spending a month with the [Knights Travails](https://www.theodinproject.com/lessons/javascript-knights-travails) problem, I've been delighted with getting back to doing some more
typical Frontend work. And I wanted to welcome the newest member in my family of frontend coding skills:
[`Test Driven Development`](https://www.theodinproject.com/lessons/node-path-javascript-testing-practice)!

The joys of starting a new project!
+ Create new Github repo
+ Create new local repo dir (Yay!)
+ Prepare directory structure for `Webpack`
+ Install [`Webpack`](https://webpack.js.org/guides/getting-started/#basic-setup)
+ Setup `package.json` and `webpack.config.js`
+ Create `.gitignore` and add `node_modules` to it
+ Install [`ESLint`](https://eslint.org/docs/latest/user-guide/getting-started#installation-and-usage)
+ Install [`Jest`](https://jestjs.io/docs/getting-started)
+ Follow the whole [`Getting Started`](https://jestjs.io/docs/getting-started) section of `Jest`(!!!)

### Sidenotes
While setting up Webpack and Jest I ran into the following problem:
I've created two js-files - one for my functions, one for testing. I followed
the [Getting Started](https://jestjs.io/docs/getting-started) guide up until the point
where it says `npm test`. My BASH printed this message: `SyntaxError: Cannot use import statement outside a module`. After about 90+ minutes of research and figuring out how to setup Jest to go
along with Webpack, I've realised that I had an `import` declaration for my stylesheet in one of 
my js-files. After commenting out the import, the test ran smoothly. Furthermore, I had to acknowledge,
that I wasn't even close to finishing the [Getting Started](https://jestjs.io/docs/getting-started) guide 🤦. 

### Rescources
https://codesweetly.com/minimax-algorithm
https://gist.github.com/Pragalbha-Patil/8f09d11cf09ad249767da0df8649f459