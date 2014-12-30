# {{pluginName}}

[![Build Status](https://travis-ci.org/gourmet/{{lcPluginName}}.svg?branch=master)](https://travis-ci.org/gourmet/{{lcPluginName}})
[![Total Downloads](https://poser.pugx.org/gourmet/{{lcPluginName}}/downloads.svg)](https://packagist.org/packages/gourmet/{{lcPluginName}})
[![License](https://poser.pugx.org/gourmet/{{lcPluginName}}/license.svg)](https://packagist.org/packages/gourmet/{{lcPluginName}})

{{@TODO description}}

## Install

Using [Composer][composer]:

```
composer require gourmet/{{lcPluginName}}
```

Because this plugin has the type `cakephp-plugin` set in its own `composer.json`,
[Composer][composer] will install it inside your /plugins directory, rather than
in your `vendor-dir`. It is recommended that you add /plugins/gourmet to your
`.gitignore` file and here's [why][composer:ignore].

You then need to load the plugin. In `boostrap.php`, something like:

```php
\Cake\Core\Plugin::load('Gourmet/{{ccPluginName}}');
```

## Usage

{{@TODO documentation}}

## Patches & Features

* Fork
* Mod, fix
* Test - this is important, so it's not unintentionally broken
* Commit - do not mess with license, todo, version, etc. (if you do change any, bump them into commits of
their own that I can ignore when I pull)
* Pull request - bonus point for topic branches

## Bugs & Feedback

http://github.com/gourmet/{{lcPluginName}}/issues

## License

Copyright (c) 2015, Jad Bitar and licensed under [The MIT License][mit].

[cakephp]:http://cakephp.org
[composer]:http://getcomposer.org
[composer:ignore]:http://getcomposer.org/doc/faqs/should-i-commit-the-dependencies-in-my-vendor-directory.md
[mit]:http://www.opensource.org/licenses/mit-license.php
