# consent-form-upload

Installation

npm i typescript -g
npm i ts-node -g
npm i nodemon -g

git clone https://github.com/admfarmer/consent-form-upload.git consent-form-upload
cd consent-form-upload
npm i
Running

cp configtxt config
npm start
open browser and go to http://localhost:3000

PM2

pm2 start nodemon --name consent-form-upload
