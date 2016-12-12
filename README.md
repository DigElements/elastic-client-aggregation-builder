# elastic-client-aggregation-builder

A Polymer Element which builds an elasticjs aggregation based on the set attributes.

### Example
```html
<elastic-client-aggregation-builder
  field="fieldName"
  name="aggName"
  type="terms"
  count="15"
  ejs-aggregation="{{ejsAgg}}">
</elastic-client-aggregation>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

