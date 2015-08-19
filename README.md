Personal Sublime Snippets
=========================

A collection of my Personal Sublime Text Snippets

**Author:** Andrés Zorro <zorrodg@gmail.com>  
**Last Edited:** 08/19/2015

Including:

| Type / Lang  | Name       | Tab Trigger | Description                          |
|--------------|------------|-------------|--------------------------------------|
| General      | author     | author      | returns my name and email ;)         |
| JavaScript   | debug      | debug       | returns console / $log .debug method |
|              | log        | log         | returns console / $log .log method   |
|              | warn       | warn        | returns console / $log .warn method  |
|              | info       | info        | returns console / $log .info method  |
|              | error      | error       | returns console / $log .error method |
| JS / Angular | module     | ngmodule    | angular module boilerplate           |
|              | directive  | ngdrtv      | angular directive boilerplate        |
|              | controller | ngctrl      | angular controller boilerplate       |
|              | service    | ngsrv       | angular service boilerplate          |
| CoffeeScript | docblock   | #*          | Generates a CoffeeScript JSDoc Block |

Also including `Preferences.sublime-settings` file and 'Hack' font face.

Remember to symlink your preferences:

```
  ln -s snippets/Preferences.sublime-settings Preferences.sublime-settings
```