# These are my notes on Command Line Args

## Rambling thoughts go here.

Time now, 14:43

Btw, we're not gonna go over Minimist or Yargs

What are cmd args? - strs, to pass info to program run through CLI of OS. 

Typically include configs or property vals. 

Example syntax

$[runtime] [script_name] [arg-1,...,argn]
 
### This is an example small heading. 
### Anyways, why use these?

* Nned to use many args and you don't wanna type em out each time
* pass info before program init
* Passed as easily reusable strigns
* Used in conjungtion with script& bash

#### Biggest cons
* Interface has steep learning curve unless you already know CLI
* Difficult to use on mobile devices


### Passing CLAs in Node.js

Node can already handle CLAs, but there are some nice 3rd party tools to help out. 

#### Process.argv
This is node's build in CLA handler.
It's a global array object handler

3 elems
0. file sys path to node exe
1. name of jsfile to be executed
2. first argument to be passed by user

Eg proccessargv.js
``` javascript
'use strict';

for (let j = 0; j < process.argv.length; j++) {
    console.log(j + ' -> ' + (process.argv[j]));
}
```

run $ node processargv.js tom jack 43
which prints 

0 -> /Users/tomzhang/.nvm/versions/node/v15.14.0/bin/node
1 -> /Users/tomzhang/Documents/LightHouseLabs/week1/d1-focal/processargev.js
2 -> tom
3 -> jack
4 -> 43

the first arg is actually at index 2, despite being the first arg

#### skipping minimist
-basically, take args and make them simpler, but in lhl right now we can just keep the whole awkward array.

I Shall Return?

#### skipping yargs
helps to parch CLAs passed to node.
Pass args in key-val pairs, then using keys. 

again, I shall return?


## Conclusion
make use of proccess.argv to pass CLAs
use minimist to simplify
use yargs for more powerful tool

done 15:07

## Keyboard Shortcuts - Important.
altab

cmd + ~, for when you have multiple chrome window

cmd-t newtab

cmd - <- ->

cmd / comment