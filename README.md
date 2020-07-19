# bhadresh-dudhat

Git-pages deployment

ng new bhadresh-dudhat
change build folder in angular.json to dist
npm i angular-cli-ghpages — save-dev

create repository with name bhadresh-dudhat on GITHUB
git remote add origin https://github.com/bhadreshdudhat/bhadresh-dudhat.git

ng build --prod --base-href https://bhadreshdudhat.github.io/bhadresh-dudhat 
npx angular-cli-ghpages — dir=dist/bhadresh-dudhat

https://bhadreshdudhat.github.io/bhadresh-dudhat 
