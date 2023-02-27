Skandia hackathon CTF 2023!

## Table of contents

- [Setup](#setup)
    - [From Sources](#from-sources)
    - [Gitpod](#gitpod)

## Setup

> Here are some different ways to run the application.

### From Sources

1. Install [node.js](#nodejs-version-compatibility)
2. Run `git clone https://github.com/antbac/skandiahack2023ctf.git --depth 1`
3. Go into the cloned folder with `cd skandiahack2023ctf`
4. Run `npm install` (only has to be done before first start or when you change the source code)
5. Run `set NODE_ENV=ctf` if on Windows or `export NODE_ENV=ctf` if on Linux
6. Run `npm start`
7. Browse to <http://localhost:3000>

### Gitpod 

1. Login to [gitpod.io](https://gitpod.io) and use <https://gitpod.io/#https://github.com/antbac/skandiahack2023ctf/> to start a new workspace.

2. After the Gitpod workspace is loaded it will start installing the required node modules. This may take a couple of minutes but once it is done it should automatically start the web application in your browser.

3. Your Juice Shop instance will then be accessible at `https://3000-<GITPOD_WORKSPACE_ID>.<GITPOD_HOSTING_ZONE>.gitpod.io`.
