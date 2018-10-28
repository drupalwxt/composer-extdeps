# Drupal WxT - External Dependency Composer Repository

This project is a Composer Repository generator for external dependencies of [Drupal WxT](https://github.com/drupalwxt/wxt) which are not already in a Composer repository.

## Usage

Merge the following JSON to your project's `composer.json` file:

```json
{
   "repositories": [
      "type": "composer",
      "url": "https://TBD"
   ]
}
```