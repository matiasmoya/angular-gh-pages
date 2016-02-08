# angular-gh-pages
Experiment with angular and GitHub pages

## Dependencies
```
Ruby >= 1.8.7 (2.2.x recommended)
sass gem (gem install sass)
npm and bower
```

## Environment setup
Make sure that you have ruby installed, and within the repository just run this:

```
gem install sass
npm install
bower install
````

Now you are ready to rock.

## Getting started
Run the development server by just typing `gulp serve`
Angular coffescript files live within `./src/app` folder, and sass files are there as well within the `./src/app/styles` folder

## Build & Deploy to gh-pages
Make a new build with `gulp build`.
You'll need to have your git repository already associated as origin, if you need to change it (beucase you may cloned from this repo) just run `git remote set-url {{your-git-repo-addess-here}}`
If you already have your repo ready, type `gulp deploy`. You don't need to create any branches or anything else, the gulp-gh-pages plugin will take care of it.

Have fun!
