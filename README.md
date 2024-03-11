# GitHub Pages Typescript Demo

This is a minimal example of a possible build/deploy process
for a GitHub Pages site with Typescript.

**This is probably not the best solution,
and definitely not production-worthy.**
This is just a nice approach if you're in my CS 1/2 class
and want to play around with Typescript while learning web development,
with minimal other overhead to learn!

## Using

Place your static files (HTML, CSS, assets, etc.) in "./out",
and write your Javascript in "./src".
Typescript is configured to compile all of your Javascript
into a single file, "./out/main.js", which the HTML file should then link
with a \<script\> tag.

Run `npm i` to install any dependencies the first time you set this project up on a given machine or codespace.

Run `npx tsc` or `npm run build` to build "main.js",
then commit and push your changes and you're good to go!
There is a GitHub Action that automatically deploys the "./out" directory
to https://\<your_username\>.github.io/\<your_repo\> .
If you want, you can try modifying the Action to compile it automatically as well!
