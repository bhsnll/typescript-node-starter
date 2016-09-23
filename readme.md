## Getting Started

*(make sure `git` and `npm` are installed on your system)*

Clone the repository.

`git clone https://github.com/bhsnll/typescript-node-starter.git`

Navigate to the directory where you cloned it in the terminal.

`cd /path/to/the/clone/typescript-node-starter`

Install dependencies.

`npm install`

Open project with VSCode (any editor would work but the project is
optimised for use with VSCode)

`code .`

Launch the VSCode debugger by pressing `F5`.

Happy coding! (Read on to understand the project organization).

## About the Project

This starter is designed to allow you to get straight to work without
worrying too much about setup. When intially looking at the project
structure with the VSCode file explorer it may seem magical. This is
because things such as the `.vscode` folder, the `node_modules` folder
and all of the `.js` files are hidden from the explorer with the VSCode
config file. To access this file go to `Code > Preferences > Workspace
Settings`. This hides a lot of the files that make the project work.

Another good spot to look to get a feel for the workings of the project
is the `package.json` file. The `scripts` section of that should give
you an idea of how things are working.

## What's with the `F5` magic?

That's a VSCode thing. You can find the configuration file at
`.vscode/launch.json`. This file has a pre-launch task which runs
the npm build script and has the `sourcemaps` option set to true.
Other than those modifications it's the default `launch.json` file
VSCode configures when you setup a Node project.