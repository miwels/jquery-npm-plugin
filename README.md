# jquery-npm-plugin
**Dependencies:**

* browserify
* uglify

**Steps:**

    mkdir dist/
    browserify entry.js --debug -o dist/bundle.js
    uglify -s dist/bundle.js -o dist/bundle.js
