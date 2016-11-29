# elastic-client-aggregation-builder

An element which builds an elasticjs aggregation based on the set attributes.

Example:
```html
    <elastic-client-aggregation-builder
        field="fieldName"
        name="aggName"
        type="terms"
        count="15"
        ejs-aggregation="{{ejsAgg}}">
    </elastic-client-aggregation>
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install
