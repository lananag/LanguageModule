# LanguageModule
This langauge module includes languages and json files that contribute to creating a module that works.

List of languages included:
English.json
Norwegian.json
Swedish.json

INSTALLATION
You can install this language module by cloning the repo. You put this into your server throught your server.js file.

USAGE:
ADD const getJoke = require("./languageModule/dictionary.js") in your server.js and call it using in a function using getJoke with the chosen language id/text sendt along.

EXAMPLE:
let language = "english" or connect to buttons with language as button id
let answer = await getJoke(language);

The button id/parameter needs to have the same name as the json file requested.



