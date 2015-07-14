
# Example configurations for Platform.sh

This repository is a collection of various example configurations demonstrating the flexibility of `Platform.sh`.

## Examples

Each example is a specific branch that you can use as a starting point for your [Platform.sh](https://platform.sh) project.

### Drupal

* [drupal/7.x](https://github.com/platformsh/platformsh-examples/tree/drupal/7.x)
* [drupal/8.x](https://github.com/platformsh/platformsh-examples/tree/drupal/8.x)
* [drupal/kickstart-2.x](https://github.com/platformsh/platformsh-examples/tree/drupal/kickstart-2.x)
* [drupal/7.x-grunt](https://github.com/platformsh/platformsh-examples/tree/drupal/7.x-grunt)
* [drupal/7.x-composer_manager](https://github.com/platformsh/platformsh-examples/tree/drupal/7.x-composer_manager)
* [drupal/8.x-commerce](https://github.com/platformsh/platformsh-examples/tree/drupal/8.x-commerce)

### Symfony

* [symfony/standard-full](https://github.com/platformsh/platformsh-examples/tree/symfony/standard-full)
* [symfony/standard-dev-full](https://github.com/platformsh/platformsh-examples/tree/symfony/standard-dev-full)
* [symfony/sandbox-full](https://github.com/platformsh/platformsh-examples/tree/symfony/cmf-sandbox-full)
* [symfony/todo-mvc-full](https://github.com/platformsh/platformsh-examples/tree/symfony/todo-mvc-full)

### Misc

* [akaneo/standard-edition](https://github.com/platformsh/platformsh-examples/tree/akeneo/standard-edition)
* [double-mysql](https://github.com/platformsh/platformsh-examples/tree/double-mysql)
* [laravel/laravel](https://github.com/platformsh/platformsh-examples/tree/laravel/laravel)
* [multiapp/drupal-symfony](https://github.com/platformsh/platformsh-examples/tree/multiapp/drupal-symfony)
* [wordpress/4.x](https://github.com/platformsh/platformsh-examples/tree/wordpress/4.x)
* [sonata/2.4](https://github.com/platformsh/platformsh-examples/tree/sonata/2.4)

## How to use

Clone one of the example branch you want to start from:

    $ git clone --branch=BRANCH-NAME git@github.com:platformsh/platformsh-examples.git my-project
    $ cd my-project

If you start from a new [Platform.sh](https://platform.sh) project, choose the ``start with an existing repository`` option and copy the ``remote add`` command. 

Paste this command into your newly created folder and push it to your [Platform.sh](https://platform.sh) project:

    $ git remote add platform PROJECT-ID@git.eu.platform.sh:PROJECT-ID.git
    $ git push -u platform HEAD:master


That's it!
