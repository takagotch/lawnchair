### lawnchair
---
https://github.com/brianleroux/lawnchair/

```js
var store = new Lawnchair({name: 'testing'}, function(store){
  var me = {key:'brian'};
  store.save(me);
  store.get('brian', function(me){
    console.log(me);
  });
});

```

```
```

```
```

