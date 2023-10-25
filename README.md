# WKND with Web Components

This experiment uses Web Components to render the WKND content
from the Edge Delivery pipeline.

See also https://github.com/hlxsites/wknd which is a "plain blocks"
variant that renders the same content, and https://wknd.site/ which
is the original AEM Classic rendering of that content.

And https://www.aem.live/home of course.

Note that we're not aiming for the same rendering as the original
WKND example, this is more meant to demonstrate how to use Web
Components efficiently in an Edge Delivery project.

## Environments
- Preview: https://main--wknd-webcomponents--bdelacretaz.hlx.page/
- Live: https://main--wknd-webcomponents--bdelacretaz.hlx.live/

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/aem-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `{repo}` directory in your favorite IDE and start coding :)
