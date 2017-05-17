# Demo Repo to experiment with Composer Builds

## Usage

1. Copy the and example Composer file from ```composer-examples/``` to ```composer.json```: ```cp composer-examples/composer-*.json composer.json```. file into the top level of your repository.
1. Run ```composer install``` to build your codebase.

See what happens!

## Tags
Checking out the tags below set the repo to a state to experiment with various commands:
* ```demo_base``` will install drupal only.
* ```demo_require``` adds the necessary installer paths to properly install themes, modules and profiles with the ```composer require``` command.
* ```demo_update_conflict_v1``` includes a composer.lock and composer.json file. Running ```composer install``` will install D8.2.6 and Drush 8.1.7, setting up the site to test ```composer update``` and explore conflicts. Note that the ```composer.json``` versioning is **too generic** in this file, on purpose.


## Resources

* [Composer](https://getcomposer.org/)
* [Acquia Remote Administration](https://docs.acquia.com/ra)
* [Acquia Automation](https://docs.acquia.com/ra/automation)
* [Acquia Automation: Composer builds](https://docs.acquia.com/ra/automation/composer)
