#React Workshop
_By Assaf Gannon_

This workshop is divided to several steps. Each step build upon the previous step and is in it's own git branch
(i.e. master, step-1, step-2 ... final). You can reset to the beginning of each step by typing
```sh
git reset --hard HEAD
```

To advance to the next step type
```sh
git checkout [next-step-branch] -f
```

## Before we begin
Make sure you have the lates [nodejs](https://nodejs.org/) version
Please clone this repository and install npm dependencies

```sh
git clone XXX react-workshop 
cd react-workshop && npm i
```

Make sure to have a decent js editor such as WebStorm, Atom, MSCode, SublimeText ets.

### Step 0 (master)
For convenience I have preset some basic elements in the app such as Webpack, Babel and hot reload

To start the dev server run:
```sh
npm start
```
Open a browser @ [http://localhost:8080](http://localhost:8080)