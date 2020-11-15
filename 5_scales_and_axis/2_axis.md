# d3 has build in function for creating axis

```javascript

    const xAxis = d3.svg.axis();

// Assign the scale
    xAxis.scale(xScale)

//  Orient the axis
    xAxis.orient("bottom")

svg.append('g') //group element
    .call(xAxis)
```