fetch-browserify-bower-demo
===========================

To clone, install & build run the following commands:-

```sh
git clone git@github.com:matthew-andrews/fetch-browserify-bower-demo.git
cd fetch-browserify-bower-demo
npm install
bower install
browserify -e main.js -o built.js -t debowerify
```
