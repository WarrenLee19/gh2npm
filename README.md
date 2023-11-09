# gh2npm
Stream github repo as targz

### Valid URL
- https://gh2npm.vercel.app/api/{author}/{repo}
- https://gh2npm.vercel.app/api/{author}/{repo}/{folder}
- https://gh2npm.vercel.app/api/{author}/{repo}?branch={branch}
- https://gh2npm.vercel.app/api/{author}/{repo}?commit={commit}
- https://gh2npm.vercel.app/api/{author}/{repo}/{folder}?branch={branch}
- https://gh2npm.vercel.app/api/{author}/{repo}/{folder}?commit={commit}

### Example
`npm install https://gh2npm.vercel.app/api/WarrenLee19/bundle-url-check-plugin?branch=main`

### Run server locally
`npm start`

### Or deploy to cloud
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/Super-Chama/gh2npm)

### how to used in `your` repository
- create a branch feature/* from main
- write feature code
- merge into your-main
- npm run prepare-release
- git push
- in your reposity
`npm install https://gh2npm.vercel.app/api/WarrenLee19/bundle-url-check-plugin?branch=main`
