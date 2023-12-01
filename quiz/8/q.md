
How to sort the unicorns based on their loves in alphabetical order.


Options
A.
```js
db.unicorns.find().sort({
  "loves": 1
})
```


B.
```js
db.unicorns.find().sort({
  "loves": -1
})
```

C.
```js
db.unicorns.find().sort({
  "loves": "desc"
})
```

D.
```js
db.unicorns.find().sort({
  "loves": "asc"
})
```