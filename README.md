# Bastelwerkstatt Shopware Theme

# Docker Setup

```shell
./psh.phar docker:start
./psh.phar docker:ssh
./psh.phar install 
```


# Build Theme

```shell
bin/console plugin:install --activate Bastelwerkstatt

bin/console theme:change

./psh.phar storefront:build
bin/console theme:refresh
```


# Links

- https://docs.shopware.com/en/shopware-platform-dev-en/getting-started/startup-guide
- https://docs.shopware.com/en/shopware-platform-dev-en/getting-started/system-installation-guides/docker-sync

- https://docs.shopware.com/en/shopware-platform-dev-en/internals/plugins/plugin-themes?category=shopware-platform-dev-en/internals/plugins&_ga=2.214966036.2032520915.1584903743-1409957321.1584343874#theme-assets
- https://docs.shopware.com/en/shopware-platform-dev-en/how-to/extending-storefront-block
