# sass-var

var()

### Description;
  var() is an extension of map-get()
  This allows you to get deep variables.

### Example use;
  $map: (
    brand: (
      primary: #000000
    )
  );

  div {
    color: var($map, brand primary);
  }
