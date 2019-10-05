# nodemon
Auto-restart node apps!
(simpler alternative to the original [nodemon](https://github.com/remy/nodemon))


`npm install thann/nodemon`

`if (require('nodemon')()) return;`

And your app will restart on any changes to the folder it's in!

This is just a wrapper for `chokidar.watch(...)`,
so you can pass any of [those options](https://github.com/paulmillr/chokidar#api).
