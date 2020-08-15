About Module
==============================================================================

This is one of the modules; helps building up the main application [ahlev.com](https://ahlev.com).

The architecture design could be found in [main app](https://github.com/ohahlev/ember-ahlev-app)

It takes care of the information about the site owner such as about information, contact information...etc

Stand Alone
------------------------------------------------------------------------------
```
ember serve
```

And go to 
```
http//localhost:4200/about
```

Installation
------------------------------------------------------------------------------

```
ember install https://github.com/ohahlev/ember-engine-ahlev-about
```

Mount
------------------------------------------------------------------------------
```
Router.map(function() {
  this.mount('ember-engine-ahlev-about', { path: 'ahlev-about'});
});
```

Compatibility
------------------------------------------------------------------------------

* Ember.js v3.12 or above
* Ember CLI v2.13 or above
* Node.js v10 or above


Usage
------------------------------------------------------------------------------

This module provides:
* components
* routes
* services


Contributing
------------------------------------------------------------------------------

See the [Contributing](CONTRIBUTING.md) guide for details.


License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
