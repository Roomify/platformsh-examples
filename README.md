# Drupal 7.0 Example for updating composer dependencies on deploy

Using composer_manager on platform.sh is slightly tricky, because the libraries directory (standard destination for composer-installed libraries) is read-only after deploy. So, we use a two-pronged approach:

1. Go to /admin/config/system/composer-manager/settings and set the 'Vendor Directory' to 'sites/default/files/composer/libraries', (Assuing a standard single-site setup) save the configuration, and press the 'Rebuild composer.json file' button.
1. Edit your .app.platform.yaml file and add/modify the deploy hook as follows:

See `.app.platform.yaml`

```yaml
In the "deploy hook" we run composer.
```
hooks:
    deploy: |
      cd /app/public/sites/default/files/composer
      composer update
```
