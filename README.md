# Banda-Gulp
### A gulpfile that pairs with the Banda Theme
------
*Requires Node Package Manager.* Instructions for installing NPM on [Windows](http://blog.teamtreehouse.com/install-node-js-npm-windows), [Mac](http://blog.teamtreehouse.com/install-node-js-npm-mac), and [Linux](http://blog.teamtreehouse.com/install-node-js-npm-linux).

1. From the terminal, in the 'wp-content' folder, run `git clone https://github.com/wphogan/banda-gulp`.

2. CD into the new 'banda-gulp' directory and run `npm install`.

3. From 'banda-gulp', run `gulp`.

4. The `gulp` command is configured with LiveReload. It automatically injects CSS edits into the browser. Add and activate LiveReload to [Chrome](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/livereload/).

 Running `gulp` will watch changes made to files in the 'sass' folder and automatically optimize images added to the 'img' folder. Sass files are compiled, auto-prefixed, and minified into a single CSS file. A source map is added to the CSS file. Errors in Sass code will produce a desktop alert.
