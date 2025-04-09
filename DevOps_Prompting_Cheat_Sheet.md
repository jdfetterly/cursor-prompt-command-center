
# DevOps & Deployment Prompting Cheat Sheet for Cursor (and Other AI Code Assistants)

Use this cheat sheet to generate, fix, or optimize infrastructure-related code and workflows—especially helpful for solo devs, consultants, and startup teams automating their deployments and environments.

---

## 1. Docker & Containerization

**Prompt Examples:**
1. Create a Dockerfile for a Node.js app that installs dependencies and runs the app.
2. Optimize this Dockerfile for smaller image size using a multi-stage build.
3. Add a `.dockerignore` file to exclude `node_modules`, `dist`, and `.env`.
4. Create a `docker-compose.yml` file for a Node.js + MongoDB stack.
5. Add health checks to the Docker container for service stability.
6. Use Alpine base image to reduce the container size.
7. Mount a volume for live code reload using Docker Compose.
8. Configure an NGINX reverse proxy in a container.
9. Set environment variables securely in Docker Compose.
10. Build and run the container with production settings.

---

## 2. CI/CD Pipelines (GitHub Actions, GitLab CI)

**Prompt Examples:**
1. Create a GitHub Actions workflow that runs tests on every push.
2. Add a deploy step to Vercel after a successful build.
3. Use GitHub Secrets to inject environment variables in the CI pipeline.
4. Run lint and test jobs in parallel before merging PRs.
5. Deploy to production only on `main` branch.
6. Cache `node_modules` in GitHub Actions for faster builds.
7. Send a Slack notification on deployment success or failure.
8. Create a manual approval step for staging deploys.
9. Use matrix builds to test across Node.js versions.
10. Auto-tag releases using commit messages.

---

## 3. Environment Variables & Config

**Prompt Examples:**
1. Load environment variables from a `.env` file using `dotenv`.
2. Differentiate between dev and prod configs using `NODE_ENV`.
3. Create a config file that supports environment-specific overrides.
4. Prevent secret keys from being committed to Git.
5. Access environment variables in a React app using `REACT_APP_` prefix.
6. Inject env vars into a Docker container at runtime.
7. Mask sensitive variables in logs.
8. Load config values from AWS Secrets Manager.
9. Provide fallback values for missing environment variables.
10. Validate required env variables on app startup.

---

## 4. Hosting & Deployment Platforms

**Prompt Examples:**
1. Deploy this app to Vercel using a single command.
2. Create a `vercel.json` config for custom routing and rewrites.
3. Configure auto-deploy to Netlify on git push.
4. Set up a GitHub webhook for triggering deploys.
5. Deploy a serverless function to AWS Lambda.
6. Create a Heroku `Procfile` for a Node.js app.
7. Add Netlify redirects for clean URLs.
8. Add environment variables to your Vercel/Netlify project.
9. Configure deployment previews for every branch.
10. Roll back a deployment to a previous version.

---

## 5. NGINX & Reverse Proxies

**Prompt Examples:**
1. Create an NGINX config to serve a static site from `/dist`.
2. Add a reverse proxy to route API requests to `localhost:3000`.
3. Enable gzip compression in the NGINX config.
4. Add caching headers for static assets.
5. Redirect all HTTP traffic to HTTPS.
6. Add a fallback to `index.html` for a SPA (Single Page App).
7. Set up load balancing across multiple Node.js instances.
8. Use Let's Encrypt to enable SSL with Certbot.
9. Serve multiple apps on different subdomains.
10. Limit request size and rate-limit IPs.

---

## 6. Monitoring & Logs

**Prompt Examples:**
1. Set up log output in JSON format.
2. Pipe logs from Node.js app to stdout/stderr for container logging.
3. Add basic uptime monitoring using UptimeRobot or StatusCake.
4. Use `winston` or `pino` for structured logging.
5. Filter sensitive data from logs before writing.
6. Monitor CPU and memory usage inside a Docker container.
7. Add alerting for failed deploys using a webhook.
8. Send logs to a log aggregation service like Logtail or Loggly.
9. Log response times for all API routes.
10. Add Prometheus-compatible metrics endpoint.

---

## Quick Reference: Common Tools & Concepts

| Area               | Tools / Terms                        |
|--------------------|--------------------------------------|
| Containers         | Docker, Compose, `.dockerignore`     |
| CI/CD              | GitHub Actions, GitLab CI/CD         |
| Config             | `.env`, `dotenv`, `NODE_ENV`         |
| Hosting            | Vercel, Netlify, AWS, Heroku         |
| Proxies & Routing  | NGINX, reverse proxy, SSL, Certbot   |
| Monitoring         | Logs, metrics, Prometheus, UptimeRobot |

---

This cheat sheet helps you automate, deploy, and maintain your projects with AI-powered prompting—even if you're not a full-time DevOps engineer.
