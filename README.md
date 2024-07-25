# kv-server documentation

- [Development](#development)
  - [Icons](#icons)
  - [Generate docs from Open API](#generate-docs-from-open-api)
- [Publishing Changes](#publishing-changes)


### Development

Run the following command at the root of your documentation (where mint.json is)

```
npx mintlify dev
```

#### Icons

Appears to use the Duotone collection from FontAwesome: https://fontawesome.com/search?o=r&f=duotone


#### Generate docs from Open API

```
npx @mintlify/scraping@latest openapi-file https://techygrrrl-kv-server.vercel.app/openapi.json -o api-reference
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard.
