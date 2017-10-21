# Event website for GitHub Field Day


## Running locally
- Clone the repository
- Make sure you have ruby installed and run `gem install jekyll` to install jekyll
- Run `npm install` to install npm dependencies
- Run `npm start` to run the site locally


## Use this repo as a template for your Field Day site

I will pretend that I'm planning a Field Day for Antarctica in 2050.

1. Create a repository in the `githubfieldday` organization called `antarctica2050`

1. Clone the `sf2017` repository: `git clone git@github.com:githubfieldday/sf2017.git`

1. Create a new folder by running `mkdir antarctica2050`

1. Copy the contents of the `sf2017` folder into your newly created `antarctica2050` folder by running `cp -r sf2017/* antarctica2050`

1. Move into the directory by running `cd antarctica2050`

1. run `git init` to initialise the git repository

1. Add the git remote of the repository you created on GitHub: `git remote add origin git@github.com:githubfieldday/antarctica2050.git`

1. Make sure you have node and npm installed

1. In the `antarctica2050` directory, search for all instances of `sf2017` and replace them with `antarctica2050`. Make sure to not include the `node_modules` and `_site` directories in your search

1. Run `npm install` to install the dependencies

1. Run `npm start` to run the site locally. You should now see a clone of the sf2017 site :tada:. You can edit the files to match your needs and the page will update live.

1. Make sure you have a `.gitignore` file that ignores `node_modules`, and `_site`, and `.publish`

1. After making the changes you want to make (update date, venue, speaker, FAQ, etc.) you can stage (`git add --all`) and commit (`git commit -m "Initial commit"`) and push to github (`git push origin master`)

1. The last thing you need to do is run `npm run deploy` (this will create a gh-pages branch and push the relevant files to it)

Your site should now be live at http://githubfieldday.com/antarctica2050 :100:
