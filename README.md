git clone git@github.com:brave/brave-browser.git
cd brave-browser
update package.json:
config.projects.chrome.tag -> 90.0.4430.93
repository.url ->"git+https://github.com/webexpertsltd/DarkTrek_Browser.git"

npm install
npm run init
npm run build