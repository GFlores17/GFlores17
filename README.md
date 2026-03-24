# George Flores

Support-focused developer with a background in API integrations, observability, and production troubleshooting. I build and maintain full-stack applications and document everything along the way.

📍 Los Angeles, CA · [LinkedIn](https://linkedin.com/in/mvsflores)

---

## Projects

**[MyVinylStats](https://myvinylstats.com)** — Vinyl collection tracker integrating the Discogs REST API  
`Node.js` `React` `Express` `MongoDB` `Prometheus` `Grafana` `AWS S3` `GitHub Actions`
- Instrumented backend with Prometheus; built Grafana dashboards monitoring HTTP request rates, error rates, and latency
- Automated CI/CD via GitHub Actions with SSH-based deployment to Hostinger
- Handles Discogs API auth, rate limiting, and upstream failure recovery

**Hangtime** — Real-time friend scheduling app  
`Node.js` `Express` `MongoDB` `WebSockets` `AWS S3`
- Diagnosed and resolved MongoDB connection pool exhaustion and Heroku dyno failures in production
- Configured AWS S3 bucket policies and CORS rules for secure file storage

**Emperor Studios** (freelance client work)  
`Python` `Node.js` `Express` `Docker` `AWS Rekognition` `Railway`
- Built an image processing pipeline: upload → Rekognition content moderation → rembg background removal → S3 → MongoDB
- Deployed a Dockerized multi-process backend (Python + Express) on Railway

---

## Open Source

Actively contributing to Python and JavaScript Discogs API clients:
- [`joalla/discogs_client`](https://github.com/joalla/discogs_client) — Python Discogs API wrapper
- [`lionralfs/discogs-client`](https://github.com/lionralfs/discogs-client) — TypeScript/JavaScript Discogs client

---

## Skills

| Area | Tools |
|---|---|
| Support & Debugging | REST APIs, OAuth 2.0, Postman, log analysis, incident response |
| Monitoring | Prometheus, Grafana |
| Infrastructure | AWS S3, AWS Rekognition, Docker, Railway, Heroku, GitHub Actions, SSH |
| Languages | JavaScript, Node.js, Python, Express, React, MongoDB, SQL |
