# Portfolio — Abdelghafour Achbani

## About Me

Full-Stack Web Developer with experience in Laravel, PHP, JavaScript, and database design. Currently training at YouCode (UM6P) in Safi, and looking for an internship.

## Links

- **GitHub:** [abdelghafourachbani1](https://github.com/abdelghafourachbani1)

## Deploy

### GitHub Pages (automatic)

This repo includes [.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml), which deploys automatically on every push to `main`.

1. Open GitHub repository settings.
2. Go to **Pages**.
3. In **Build and deployment**, set **Source** to **GitHub Actions**.
4. Push to `main` and wait for the workflow to finish.

### Any Server (Nginx / Docker)

You can deploy as a static site on any server.

Using Docker:

```bash
docker build -t portfolio-internship .
docker run -d -p 8080:80 --name portfolio-site portfolio-internship
```

Then open `http://localhost:8080`.

The repo includes:

- [Dockerfile](Dockerfile)
- [nginx.conf](nginx.conf)
- [.nojekyll](.nojekyll)
