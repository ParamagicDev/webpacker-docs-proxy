# Pulls down the docs from Webpacker

## Getting started

```bash
git clone
cd webpacker-docs-proxy
bundle install && yarn install
```

Create a `.env` file and add an `GITHUB_API_TOKEN` variable.

```bash
# .env

export GITHUB_USER="myusername"
export GITHUB_API_TOKEN="1234"
```

Finally run:

```bash
source .env && yarn start
```

and then navigate to `localhost:4000` to view your site.
