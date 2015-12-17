# sass-var

`var()`

### Description;
  `var()` is an extension of [`map_get()`](http://sass-lang.com/documentation/Sass/Script/Functions.html#map_get-instance_method).
  This allows you to get deep nested variables.

### Example use;
<pre>
  $map: (
    brand: (
      primary: #000000
    )
  );

  div {
    color: var($map, brand primary);
  }
</pre>
