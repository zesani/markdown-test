# hello Vuejs
### อิอิ ก

```
 สุดยอดไปเบยยย
```

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>

  </body>
</html>
```

```javaScript
function stringLength(str) {
    var count = 0
  for (var i = 0; i < str.length; i++) {

    if(str[i]>='A'&& str[i] <='Z')
      count++
    if(str[i]>='a'&& str[i] <='z')
      count++
  }
  return count;
}
var chai = require('chai')
var assert = chai.assert


assert.equal(stringLength("kitisak"),7)
assert.equal(stringLength("k"),1)
assert.equal(stringLength("ki"),2)
assert.equal(stringLength("kiti"),4)
assert.equal(stringLength("kitisa"),6)
assert.equal(stringLength("45"),0)
assert.equal(stringLength("45fsj"),3)
assert.equal(stringLength("45fsj*-"),3)

```
