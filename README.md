# Magento 2
Setting up magento 2 DB
## Setting Up Magento 2
```bash
    bin/magento setup:install \
    --base-url=http://local.magento.test \
    --db-host=localhost \
    --db-name=magento2 \
    --db-user=magento \
    --db-password=magento123 \
    --admin-firstname=admin \
    --admin-lastname=admin \
    --admin-email=admin@admin.com \
    --admin-user=admin \
    --admin-password=admin123 \
    --language=en_US \
    --currency=USD \
    --timezone=America/Chicago \
    --use-rewrites=1 \
    --search-engine=elasticsearch7 \
    --elasticsearch-host=localhost \
    --elasticsearch-port=9200
```