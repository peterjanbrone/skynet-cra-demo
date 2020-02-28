# Skynet Create React App Demo

The Create React App demo works on Skynet almost out of the box.  
You can simply clone it from the [Create React App](https://github.com/facebook/create-react-app) project.

## Required Changes

In `package.json`, update the `homepage` so the App is built using a relative path, rather than the root.
```
{
  ...
  "homepage": ".",
  ...
```

## Deployment

Deploying the CRA app is very easy. First we need to build the project using `yarn`.

### Install Dependencies
```bash
yarn
```

### Build Project
```bash
yarn build
```

### Deploy to Skynet

You can deploy the dapp to Skynet by uploading the entire buildfolder at siasky.net.  
This will give you a skylink, which houses your dapp. To access the App,
simply navigate to `https://siasky.net/[skylink]/build/index.html`.

## SkyDapp URL
https://siasky.dev/vAOiV66coNhbnftggC0sTFiywK0ZbxRe8l2k1y3KRumeZw/build/index.html
