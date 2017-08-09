<div align="center">
  <img width="200" height="200"
    src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg">
  <a href="https://docker.com">
    <img width="200" height="200" vspace="" hspace="25"
      src="https://cdn.worldvectorlogo.com/logos/docker.svg">
  </a>
  <h1>Node 8.2.1 Deployment Image</h1>
  <p>Docker Repository for my NodeJS deployment Image.<p>
</div>

### Usage
```bash
# config.yml
    docker:
      - image: d3vaint0ne/docker-node8-lts
```

Docker NodeJS 8.2.x deployment image including NVM, PM2 & demo SSL certificates installed.

> The included certs are for DEMO PURPOSES ONLY ( localhost https ). Don't deploy them to anythign you care about.
