## Getting Started

*(Make sure `git` and `npm` are installed on your system. And, while not required,
using VSCode as your editor is highly recommended.)*

Clone the repository.

`git clone https://github.com/bhsnll/typescript-node-starter.git`

Navigate to the directory where you cloned it in the terminal.

`cd /path/to/the/clone/typescript-node-starter`

Install dependencies.

`npm install`

Open project with VSCode (any editor would work but the project is
optimised for use with VSCode)

`code .`

Set a breakpoint on line 3 of `index.ts`.

Launch the VSCode debugger by pressing `F5`.

Happy coding! (Read on to understand the project organization).

## About the Project

This starter is designed to allow you to get straight to work without
worrying too much about setup. When intially looking at the project
structure with the VSCode file explorer it may seem magical. This is
because things such as the `node_modules` folder and all of the `.js`
files are hidden from the explorer with the VSCode config file. To access
this file go to `.vscode/settings.json`. This hides some of the files that
make the project work.

Another good spot to look to get a feel for the workings of the project
is the `package.json` file. The `scripts` section of that should give
you an idea of how things are working.

## What's with the `F5` magic?

That's a VSCode thing. You can find the configuration file at
`.vscode/launch.json`. This file has a pre-launch task which runs
the npm build script and has the `sourcemaps` option set to true.
Other than those modifications it's the default `launch.json` file
VSCode configures when you setup a node project.

## Why?

I created this because I find myself doing lots of little node experiments.
Being a typescript fan, I find myself setting up the whole
transpilation process every single time. And of course I end up setting up the
debugger as well. Doing this over and over again grew tiresome so I decided to make
this repository. You may notice a few of my prefrences have slipped in here
(such as enabling auto-save at the workspace level in VSCode along with a
few tslint rules). I intend this mainly for personal use so it makes sense for
me to include these things. Obviously, however, I'm happy to share this tool
with others. I welcome any suggestions or comments.

## VSCode Extension Recommendations

[npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)

[TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)