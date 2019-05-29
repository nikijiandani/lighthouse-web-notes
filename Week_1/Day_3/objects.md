# Objects

Objects have a constant time lookup.
Looking up something in an array takes longer. 

Anything apart from primitives is an object.

```javascript
//for in loop
for(var key in instructor){
    var value = instructor[key];
}

var keys = Object.keys(instructor);
console.log(keys);

```
