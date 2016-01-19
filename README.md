# sass-get

`get()`

### Description;
  `get()` is an extension of [`map-get()`](http://sass-lang.com/documentation/Sass/Script/Functions.html#map_get-instance_method). This allows you to get deep nested variables.

For more information please read this [article](http://cereal.co/deep-nested-variables-in-sass/)

### Example use;
<pre>
  @import 'function.var';
  
  $map: (
    brand: (
      primary: #000000
    )
  );

  div {
    color: get($map, brand primary);
  }
</pre>
