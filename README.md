# GSD Updates sites
lists releases (only docker image assets) of https://github.com/Cojonas/gsd-frontend-backend"


## dev
### cd server && SHARED_FOLDER_DOCKER=/home/user/path/to/folder npm start
### cd client && npm start


## production
### cd client && npm run build
include built files in server/public/appfiles
### cd server && SHARED_FOLDER_DOCKER=/home/user/path/to/folder node server.js
