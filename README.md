# Instagram Feed GraphQL

**Instagram Feed GraphQL is a part of MageINIC Instagram Feed extension that adds GraphQL features.** This extension extends Instagram Feed definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/instagram-feed-graphql

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Instagram Feed GraphQL requires installing [MageINIC Instagram Feed](https://github.com/mageinic/Instagram-Feed) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/instagram-feed
```

## 2. How to use

- To view the queries that the **MageINIC Instagram Feed GraphQL** extension supports, you can check `Instagram Feed GraphQl Extension User Guide.pdf` Or run `InstragramFeed Graphql.postman_collection.json` in Postman.

## 3. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
