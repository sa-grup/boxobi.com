# Boxobi.com

This repository contains the source code for the Boxobi.com website, a static website built with [Hugo](https://gohugo.io/).

## Local Development

To run the website locally for development and testing, you'll need to have Hugo installed. You can find installation instructions in the [official Hugo documentation](https://gohugo.io/getting-started/installing/).

Once Hugo is installed, you can run the local development server with the following command:

```bash
hugo server -D
```

This will start a local server, and you can view the website by opening your web browser to `http://localhost:1313`. The `-D` flag ensures that draft content is also displayed.

## Deployment

This project is configured for automatic deployment using GitHub Actions. Any changes pushed to the `main` branch will be automatically built and deployed to the live website.

To deploy your changes, simply commit them and push to the `main` branch:

```bash
git add .
git commit -m "Your descriptive commit message"
git push origin main
```