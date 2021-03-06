# ember-json-api

This is a [JSON API](http://jsonapi.org) adapter for [Ember Data](http://github.com/emberjs/data) 1.0 beta 2, that extends the built-in REST adapter. Please note that Ember Data and JSON API are both works in progress, use with caution.

### Download
- [json_api_adapter.js](http://raw.github.com/daliwali/ember-json-api/master/dist/json_api_adapter.js) (3.3 kb)
- [json_api_adapter.min.js](http://raw.github.com/daliwali/ember-json-api/master/dist/json_api_adapter.min.js) (1.6 kb)

### Usage
```javascript
App.ApplicationAdapter = DS.JsonApiAdapter;
```

### Build It Yourself

You will need `grunt-cli` installed on your system: `npm install -g grunt-cli`. Then run:

```
$ npm install && grunt
```

The output files go in the `dist` folder.

### Untested (not working)
- top-level `meta` and `links` objects
- URL-style JSON API
