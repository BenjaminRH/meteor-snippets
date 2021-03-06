# Meteor Snippets for Sublime Text 2/3

Some snippets for working with the [Meteor](http://meteor.com) framework.

Includes snippets for
 * CoffeeScript (WIP)
 * HTML (done)
 * JavaScript (done)

## Installation

You can install them now via [Package Control](http://wbond.net/sublime_packages/package_control) (search for "Meteor Snippets") or manually via git:

##### OS X
```
git clone git://github.com/mrtnbroder/meteor-snippets.git ~/Library/Application Support/Sublime Text 2/Packages/Meteor Snippets
```

##### Linux
```
git clone git://github.com/mrtnbroder/meteor-snippets.git ~/.config/sublime-text-2/Packages/Meteor Snippets
```

##### Windows
```
git clone git://github.com/mrtnbroder/meteor-snippets.git %userprofile%\AppData\Roaming\Sublime Text 2\Packages\Meteor Snippets
```

## Examples

__tp__
```html
<template name="main">
	...
</template>
```

Meteor.render
```javascript
Meteor.render(function () {
	...
});
```

Meteor.publish
```javascript
Meteor.publish("name", function () {
	...
});
```

__if__
```handlebars
{{#if guyIs "male"}}
	...
{{/if}}
```

__ea__
```handlebars
{{#each player}}
	...
{{/each}}
```

... and a whole lot more!

## Todo's

 * remap the tabTriggers
 * add CoffeeScript Methods
 * add HTML Methods

## Contribute

you got some neat Meteor snippets you want to share? fork this repro and send me a pull request so I can take a look at them!