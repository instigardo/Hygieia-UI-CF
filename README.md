
## Hygieia℠ UI - Cloud Foundry

### Requirements

- NodeJS
- npm
- gulp
- bower

#### Mac OS X

    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    brew install node
    npm install -g bower
    npm install -g gulp

Pull down bower_components that's configured with bower:

    bower install

Will need up update the ngFitText bower.json file to point to 'src/ng-FitText.js' instead of '/src/ng-FitText.js'

#### Windows

Install NodeJS using the MSI package available at: http://nodejs.org/download/

Issue the following commands via command line:

	npm install -g bower
	npm install -g gulp

Use Git Shell to install bower in the following manner; do so from your project's root directory:

    bower install
	select option 2 when prompted for user input

Push it to cloudfoundry (Remember to edit index.js to point to your /api)

    cf push

for more info look into 

https://github.com/capitalone/Hygieia
