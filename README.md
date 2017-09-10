# node_starters1_switch
after04-09-2017intro

after https://github.com/GossJS/node_starters1 was created we made some changes to it 04/09/2017

including npm-run-all

so let's fix those changes here.

so we'll use `npm-run-all --parallel launch build`

where

`launch` is `nodemon --watch`

and

`build` is `babel --watch src --out-file bundle.js`

not to forget make `bundle.js` a main file in package.json

---

we can also always say `./node_modules/babel-cli/bin/babel-node.js my.js` to launch script through babel without building
