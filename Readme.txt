#
## use node v5
## nvm use 5
#

#
## Install json-server & run
#
->$ npm install -g json-server
->$ json-server --watch db.json

http://localhost:3000


- Review db.json for REST endpoints and JSON returned 
- Review /public for HTML files
-- index.html
-- quotesummary.html
-- quotepurchase.html






#Trying to get routes working
->$ json-server --watch db.json --routes routes.json
