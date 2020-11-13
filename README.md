## My Directions 

1. Open GitHub and Fork and Clone the Repo.

2. Open the the file location using your terminal.
3. Create your JS file which will be called `index.js`
```bash
touch index.js
```
4. In terminal, whichin the project folder, initialize the node command.
```
npm init
```

5. Give the package name: ours will be node_practice.

6. Since it is the 1st version it will be listed as 
```bash
1.0.0
```
7. Click entet when it states the license and click Yes when it asks if it is OK?

8. Now execute the JS file using a NPM command in terminal.

In the package.json file created, add the following code:
```json
"start" : "node index.js"
```
Then run the node start command in the terminal.
```bash
$ node start
(this will show the code you have written in the js file.)
```
9. Add someones interesting NPM package. Find an interesing NPM pacakge

[https://www.npmjs.com/package/@ultraq/array-utils]

10.  Run the insall code in your terminal 
```bash
npm i @ultraq/array-utils
```
11. Now add a .gitignore in the Node Modules folder.
        1. Open terminal and go to the node_modules fodler.
        2. Run the following code.
            ```bash
                npm i create-gitignore
            ```
12. Commit and Push to git hub!



# Node Modules Practice

- [ ] Fork and clone this repo
- [ ] Initialize node in your cloned repo so it becomes a node project!

## Make your own module

- [ ] Create a node module that stores an array of your favorite foods
- [ ] Import that module into your `index.js`
- [ ] Write code in your `index.js` so when you run your app, it loops through the array, printing all of your favorite foods to the console

## Experiment with implementing a package

- [ ] Find 3 [npm](https://www.npmjs.com/) packages that look interesting
- [ ] Experiment with incorporating them into this node project, just like we did with moment

## Add to your Node app instructions readme

- [ ] Add notes about how to create and import node modules to your Node/Express app readme, along with instructions about adding a `.gitignore`
- [ ] Paste the link to your repo in this the readme of this assignment

## Finally, .gitignore and submit a PR!

- [ ] Add a `.gitignore` to this assignment, so the `node_modules` folder doesn't upload to Github
- [ ] Submit this assignment by making a `pull request`


