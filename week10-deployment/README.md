# Deployment

## Static site on Netlify

1. Push this repository to GitHub.
2. In Netlify, choose **Add new site → Import an existing project**.
3. Select the repository and set the publish directory to `week10-deployment/static-site`.

## Dynamic app

# Deployment

## Static site on Netlify

1. Push this repository to GitHub.
2. In Netlify, choose **Add new site → Import an existing project**.
3. Select the repository and set the publish directory to `week10-deployment/static-site`.

## Dynamic app

For the included Node service, set the root directory to `week10-deployment/dynamic-site`, the build command to `npm install`, and the start command to `npm start`. Set secrets in the host's environment settings. The included `render.yaml` provides a deployment definition for Render, and `netlify.toml` configures the static site.For the included Node service, set the root directory to `week10-deployment/dynamic-site`, the build command to `npm install`, and the start command to `npm start`. Set secrets in the host's environment settings. The included `render.yaml` provides a deployment definition for Render, and `netlify.toml` configures the static site.# Deployment

## Static site on Netlify

1. Push this repository to GitHub.
2. In Netlify, choose **Add new site → Import an existing project**.
3. Select the repository and set the publish directory to `week02-portfolio` (or another static week).

## Dynamic app

For a Node service, set the build command to `npm install` and start command to `npm start`. Set secrets such as `JWT_SECRET` in the host's environment settings. Heroku's free tier is no longer available; use a current provider such as Render, Railway, Fly.io, or AWS.
