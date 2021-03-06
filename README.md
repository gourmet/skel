# {{pluginName}}

[![Build Status](https://travis-ci.org/gourmet/{{lcPluginName}}.svg?branch=master)](https://travis-ci.org/gourmet/{{lcPluginName}})
[![Total Downloads](https://poser.pugx.org/gourmet/{{lcPluginName}}/downloads.svg)](https://packagist.org/packages/gourmet/{{lcPluginName}})
[![License](https://poser.pugx.org/gourmet/{{lcPluginName}}/license.svg)](https://packagist.org/packages/gourmet/{{lcPluginName}})

{{@TODO description}}

## Install

Using [Composer][composer]:

```
composer require gourmet/{{lcPluginName}}:dev-master
```

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

To ensure your PRs are considered for upstream, you MUST follow the CakePHP coding standards. A `pre-commit`
hook has been included to automatically run the code sniffs for you:

```
ln -s ../../contrib/pre-commit .git/hooks/.
```

## Bugs & Feedback

http://github.com/gourmet/{{lcPluginName}}/issues

## License

Copyright (c) 2015, Jad Bitar and licensed under [The MIT License][mit].

[cakephp]:http://cakephp.org
[composer]:http://getcomposer.org
[composer:ignore]:http://getcomposer.org/doc/faqs/should-i-commit-the-dependencies-in-my-vendor-directory.md
[mit]:http://www.opensource.org/licenses/mit-license.php
