**How to start with a new project.**
 
- We start out by doing Yo h5bp

- Check to see what files you don't need, that came standard with boilerplate. 

- git add css/ js/ index.html LICENTSE.txt

- git clean -n      then      git clean -f

- rm -rf img

- Yo Mocha

- cd test

- git ignore bower_components

- ls -al (shows all files even the ones with the dot) git ignore things I don’t need)

- git add . / git commit/ git push 

- npm init

- bower init

- git ignore node_modules (if you have them?)

**CLEANING UP**

- Push changes again

- Edit package.son files to add Start and Test by adding "start": "browser-sync start --server --files='index.html, js/**/* .js,css/**/* .css/'"

- “test": "browser-sync start --server --files=‘test/spec/**/*.js/‘ —startPath test/index.html”

- Test NPM start

- Clean out Index.html
