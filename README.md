# Using Netlify Edge Functions with Astro

A starter template for building a Server-Side Rendered (SSR) [Astro](https://astro.build/) app with [Netlify Edge Functions](https://docs.netlify.com/netlify-labs/experimental-features/edge-functions/).

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/sarahetter/astro-netlify-edge-starter)

This uses Astro's [`@astrojs/netlify`](https://github.com/withastro/astro/tree/main/packages/integrations/netlify) package to deploy your site with SSR enabled.

|:----------|:-----------------------------------------------|
| Demo Site | https://astro-edge-functions-demo.netlify.app/ |

### Local development

Within this project directory:

```
npm install
npm run dev
```

### Deploying the project in the command line

1. Install the [netlify cli](https://docs.netlify.com/cli/get-started/) globally:
```
npm install netlify-cli -g
```
2. Deploy your site:
```
netlify deploy --build
```
