How to start out a new project (outline- rough)

START NEW PROJECT
 
Yo h5bp

Remove shit files
git add css/ js/ index.html LICENTSE.txt

git clean -n      then      git clean -f

rm -rf img

Yo Mocha

cd test

git ignore bower_components

ls -al (shows all files even the ones with the dot) git ignore things I don’t need)

git add . (gets all the files staged)
git push 

npm init

bower init

git ignore node_modules (if you have them?)

CLEANING UP

Push changes again

Edit package.son files to add Start and Test
"start": "browser-sync start --server --files='index.html, js/**/* .js,css/**/* .css/'"

Test NPM start

Clean out Index.html

Add to bower.son file
"start": "browser-sync start --server --files='index.html, css/, js/‘”

“test": "browser-sync start --server --files=‘test/spec/**/*.js/‘ —startPath test/index.html”

TO SAVE ON

bower install —save jQuery

bower install —save chai/mocha
