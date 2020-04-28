# 25Watts Setup for Magento2

Metapackage to install a set of modules that will improve the configuration of your store for websites that are running in Argentina.

Current included modules are:

* [Mugar_ArgentinaRegions](https://github.com/holamugar/module-argentina-regions)
* [Mageplaza_SocialLogin](https://github.com/mageplaza/magento-2-social-login)
* [Mageplaza_SpanishArgentinaLanguagePack](https://github.com/mageplaza/magento-2-spanish-argentina-language-pack)
* [MercadoPago_Core](https://github.com/mercadopago/cart-magento2)
* [Strategery_Infinitescroll](https://github.com/Strategery-Inc/Magento2-InfiniteScroll)

## Installation

Use [composer](https://getcomposer.org/) to install Mugar Argentina Setup metapackage.

```
composer require watts25/magento2-setup
```

Then you'll need to activate the included modules.

```
bin/magento module:enable Mugar_ArgentinaRegions
bin/magento setup:upgrade
bin/magento cache:clean
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

### How to create a PR

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## License

[MIT](https://choosealicense.com/licenses/mit/)