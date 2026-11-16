# MERN capstone blueprint

Build on the notes app with these production pieces:

- `client/`: React UI using Vite
- `server/`: Express routes and middleware
- MongoDB: notes collection with Mongoose
- Authentication: hashed passwords and short-lived JWTs
- Deployment: host the client and API separately, then configure the client API URL with an environment variable

Suggested API: `GET/POST /api/notes`, `PUT/DELETE /api/notes/:id`, and `POST /api/auth/login`.

Before deployment, configure CORS, validation, rate limiting, HTTPS, secure cookies, and environment variables. Never use the development JWT secret in production.
