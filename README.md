# APIs_Newman
Collections with publics APIs for play in newman with report.

Each folder contains 1 json file from the collection and its respective environment json.

Link installation postman: https://learning.postman.com/docs/getting-started/installation-and-updates/
Link installation newman: https://www.npmjs.com/package/newman
Link installation newman-reporter-htmlextra: https://www.npmjs.com/package/newman-reporter-htmlextra

After installations, inside the project's root execute command as example:

$ newman run Breaking_Bad.postman_collection.json -e Breaking_Bad.postman_environment.json -r htmlextra,cli


