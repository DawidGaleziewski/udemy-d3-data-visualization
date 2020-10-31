SVG - xml markup based imaged. png images are raster images. SVG is created using vectors and not pixesl/rasters like png

SVG uses: shapes, gradients (paint), filters (blur and other effects)

SVGs are html objects and can be styled by CSS


```HTML

<svg>
    <rect width="50" height="200", style="fill:blue" />
</svg>

```

D3.js can create this object in html:

```javascript
d3.select("body").append('svg').apend('rect').attr("width", 50).attr("height", 200).style('fill', "blue")

```

## How svg draws things?
SVG uses coordinate system to draw
It has 4 points on a viewport

top-left: 0,0
top-right: 300,0
bottom-left: 0,300
bottom-right: 300,300

on X axis the first coordinate increments
on Y axis the second coordinate increments
X+,Y+