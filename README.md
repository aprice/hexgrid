hexgrid
=======

Hexagonal tile grids in pure HTML and CSS.

Example:
```html
<!DOCTYPE html>
<html>
  <head>
    <script src="hexgrid.js"></script>
    <link rel="stylesheet" href="hexgrid.css"/>
  </head>
  <body>
    <hex-grid>
      <hex-row>
        <hex-tile>1</hex-tile>
        <hex-tile>2</hex-tile>
      </hex-row>
      <hex-row>
        <hex-tile>3</hex-tile>
        <hex-tile>4</hex-tile>
      </hex-row>
    </hex-grid>
  </body>
</html>
```

The `hex-grid` `getTile()` method and the `hex-tile` `getPosition()` method both require jQuery to be available.
