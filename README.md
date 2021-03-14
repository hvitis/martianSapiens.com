# Martian Sapiens || Blog

Based on Netlify CMS template for Gridsome


## Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/suits-at/netlifycms-gridsome)

### Enable Identity

Enable the netlify identity service at https://app.netlify.com/sites/YOUR-SITE/settings/identity. For exact instructions see https://www.netlify.com/docs/identity/. You might want to enable Git Gateway as well https://www.netlify.com/docs/git-gateway/. 

### Edit content

Access `yourwebsite.com/admin`, e.g. `netfliycms-gridsome.netlify.com/admin` or locally this might be  `localhost:3000/admin`.

## Install locally

### 1. Install Gridsome CLI tool if you don't have

`npm install --global @gridsome/cli`

### 2. Install this starter

1. `gridsome create my-gridsome-site https://github.com/suits-at/netlifycms-gridsome`
2. `cd my-gridsome-site` to open folder
3. `gridsome develop` to start local dev server at `http://localhost:8080`
4. Happy coding 🎉🙌
