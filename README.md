# filter-behavior

A collections of filters such as the search facets.

Function Name | Parameters | Returns
--------------|------------|---------
DigBehaviors.FilterBehavior.areAllFacetsDisabled | One facet and One array of items to ignore | Returns whether all the items in the given search facets collection are disabled.
DigBehaviors.FilterBehavior.getFacetDates | One facet | Returns the two-element array of start and end dates from the given date search facet.
DigBehaviors.FilterBehavior.getFacetTerms | One facet | Returns the array of enabled query terms from the given search facet.
DigBehaviors.FilterBehavior.getEntityPageFilterItems | One array of items to ignore | Returns the array of query items from the given entity page filter (can be used for terms or dates).

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

