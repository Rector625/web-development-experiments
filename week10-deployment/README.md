# Deployment

## Static site on Netlify

1. Push this repository to GitHub.
2. In Netlify, choose **Add new site → Import an existing project**.
3. Select the repository and set the publish directory to `week10-deployment/static-site`.

## Dynamic app

For the included Node service, set the root directory to `week10-deployment/dynamic-site`, the build command to `npm install`, and the start command to `npm start`. Set secrets in the host's environment settings. The included `render.yaml` provides a deployment definition for Render, and `netlify.toml` configures the static site.
