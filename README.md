# Bar Labels plugin for Chartist.js
This plugin displays the value in labels above your bars in a bar chart for [Chartist.js](https://gionkunz.github.io/chartist-js/).

Please visit [http://gionkunz.github.io/chartist-js/plugins.html](http://gionkunz.github.io/chartist-js/plugins.html) for more information.

## Available options and their defaults
``` javascript
var defaultOptions = {
  labelClass: 'ct-label',
  labelOffset: {
    x: 0,
    y: -10
  },
  textAnchor: 'middle'
};
```

## Sample usage in Chartist.js
``` javascript
var chart = new Chartist.Bar('.ct-chart', {
  labels: [1, 2, 3, 4, 5, 6, 7],
  series: [
    [1, 5, 3, 4, 6, 2, 3],
    [2, 4, 2, 5, 4, 3, 6]
  ]
}, {
  plugins: [
    ctBarLabels({
      labelClass: 'ct-bar-label',
      textAnchor: 'middle'
    })
  ]
});
```
