
## Selections
```javascript
    d3.select("body")
```

## Append
```javascript
    .append('body')
```

## Style operators
```javascript
    .attr('width', 50)
    .style('fill', 'blue')
```


# Chaining syntax with whitespace
```javascript
    d3.select("body")
        .append('svg')
        .append('rect')
            .attr('width', 50)
            .attr('height', 50)
            .style('fill', 'blue')
```