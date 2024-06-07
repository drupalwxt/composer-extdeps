# Drupal WxT - External Dependency Composer Repository

This project is a Composer Repository generator for external dependencies of [Drupal WxT](https://github.com/drupalwxt/wxt) which are not already in a Composer repository.

This mostly includes:

- [WET-BOEW](https://github.com/wet-boew/wet-boew)
- [GCWeb](https://github.com/wet-boew/GCWeb)

## Usage

Merge the following JSON to your project's `composer.json` file:

```js
{
   "repositories": [
      "type": "composer",
      "url": "https://drupalwxt.github.io/composer-extdeps/"
   ]
}
```
