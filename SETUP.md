<!-- blog -->
https://blog.railway.app/p/calendso


<!-- setup local env -->
brew upgrade railway
railway login / railway login --browserless
railway link
  select project


<!-- set up the database schema -->
railway run npx prisma db push


<!-- open local -->
railway open

<!-- user pass generated with -->
https://bcrypt-generator.com/

<!-- after user created -->
railway run yarn dev

<!-- prod -->
railway up
