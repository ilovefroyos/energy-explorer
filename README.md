# Community Energy Explorer #

Community Energy Explorer - http://energyexplorer.ca/

### Technologies Used: ###

* JS/Node JS
* HTML
* CSS - SASS/COMPASS - http://sass-lang.com/ and http://compass-style.org/
* Twitter Bootstrap

### How do I get set up? ###

* Install NodeJS - https://nodejs.org/en/
* Install Ruby - http://www.ruby-lang.org/en/documentation/installation/
* Install Compass and read documentation - http://compass-style.org/install/
* Before making changes to the styles, browse to /assets/styles/cee, open command window in the root folder of styles, run the following command: compass watch
* Other alternative to making changes to the styles is to double-click on the file "compass-watch.bat"
* Run npm install in the command line if you do not see a node_modules folder with all the modules installed. This has to be done at the folder level where app.js exists.
* To run the web application, open command window in the root folder of the website and execute the following command: node app.js
* View the app on localhost:5000 in your web browser.

### File Structure ###

*.vscode (not required unless running node via Visual Studio Code)
*--/ launch.json
*assets        # JavaScript/CSS/Images
*--/ bootstrap (twitter bootstrap files)
*--/ images
*--/ js (all other javasript files)
*--/ styles (all other stylesheets)
*    --/ .sass-cache (used by Compass framework)
*	--/ cee (folder initialized by compass to store all stylesheets)
*	--/--/ sass (this is where you write your styles. Compass converts it to css)
*	--/--/ css (all the converted css files. This is what you add to the <link> tag in HTML
*    --/--/ compass-watch.bat (run this file before making changes to styles. This watches the changes in scss folder and converts it to css.)
*    --/--/ config.rb (configuration file for compass. Do not make changes without understanding the docmentation on Compass website)
*node_modules (Folder where all node modules are installed.)
*routes       (Contains routing files)
*    --/ main.js (Contains all primary routes for the website)
*views (Contains all html files - coded using swig templating - http://paularmstrong.github.io/swig/ )
*    --/ Components (also contains html file but only resuable components such as navbars, footers, etc)
*.gitignore (list of folders to ignore when pushing changes to repositories using GIT
*app.js (Main entry file to start a node server)
*package.json (Created by node to save configurations and list of packages installed)
*README.md (Documentation for the project)

### Who do I talk to? ###

* Jon Salter
* Utkarsh Saxena