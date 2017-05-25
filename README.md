# Shopify Theme

[![N|Solid](https://dl.dropboxusercontent.com/s/8bbyrq6xcdxdfde/logo.gif)](https://nodesource.com/products/nsolid)

A theme for [Shopify](https://www.shopify.com/) stores built with the [Slate](https://shopify.github.io/slate/) theme scaffolding tool.

### Get started developing this theme

```
    cd path/to/local/directory`
    git clone https://github.com/akiryk/shopifyTheme.git
    touch config.yml
```
 Open config.yml and add the correct password, theme_id, and store name:
```yml
development:
  password: add password here for your shopify store
  theme_id: "a string ID"
  store: store-name.myshopify.com
  ignore_files:

production:
  password:
  theme_id: "live"
  store: store-name.myshopify.com
  ignore_files:
```
Run `slate build` or `slate start` to build and watch. See the [Slate documentation](https://shopify.github.io/slate/) for details.
