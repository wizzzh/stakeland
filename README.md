# stakeland
https://github.com/wizzzh/stakeland
## intall npm dependencies
npm install
## Copy the environment variables to .env and change the values
cp .env.example .env
## Initialize the database
npx prisma generate
npx prisma migrate deploy
## Run the dev server
npm run dev
## Open the app in your browser
Visit http://localhost:3000 in your browser.
