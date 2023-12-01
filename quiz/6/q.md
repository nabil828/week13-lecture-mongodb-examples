
How to remove "chocolate" from the list of foods unicorn Solnara loves.


Options

A.
```js
db.unicorns.update({
  "name": "Solnara"
}, {
  $pull: {
    "loves": "chocolate"
  }
})
```

B.
```js
db.unicorns.update({
  "name": "Solnara"
}, {
  $pull: {
    "loves": ["chocolate"]
  }
})
```

C.
```js
db.unicorns.update({
  "name": "Solnara"
}, {
  $pull: {
    "loves": { $in: ["chocolate"] }
  }
})
```

D.
```js
db.unicorns.update({
  "name": "Solnara"
}, {
  $pull: {
    "loves": { $nin: ["chocolate"] }
  }
})
```