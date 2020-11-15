# Scaling
'Scales are functions that map from an input domain to an output range'

- input domain - min and max of the values. I.E. min and max sales numbers
[150k, 130k, 225k, 350k]  scale of 130-350

- output range 10-100 pixel range


d3 has build in function for scales

```javascript
    const scale = d3.scale.linear() // log and pow another options for scales
    .domain([130, 350]) // input min and max of sales values
    .range([10,100]) // output pixels for SVG

    // using the scale function
    scale(300); // output 79.54
```