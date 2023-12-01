How to increase the weight of unicorn Leia by 20 pounds.


Options

A.
```js
db.unicorns.update({
  "name": "Leia"
}, {
  $inc: {
    "weight": 20
  }
})
```

B.
```js
db.unicorns.update({
  "name": "Leia"
}, {
  $inc: {
    "weight": -20
  }
})
```

C.
```js
db.unicorns.update({
  "name": "Leia"
}, {
  $dec: {
    "weight": 20
  }
})
```

D.
```js
db.unicorns.update({
  "name": "Leia"
}, {
  $add: {
    "weight": 20
  }
})
```