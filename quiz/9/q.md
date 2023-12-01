How to get the heaviest male unicorn that loves both apples and carrots.

Options

A.
```js
db.unicorns.find({
  "loves": { $all: ["apple", "carrot"] }
}).sort({
  "weight": -1
}).limit(1)
```

B.
```js
db.unicorns.find({
  "loves": { $all: ["apple", "carrot"] }
}).sort({
  "weight": 1
}).limit(1)
```

C.
```js
db.unicorns.find({
  "loves":  ["apple", "carrot"] 
}).sort({
  "weight": -1
}).limit(1)
```

D.
```js
db.unicorns.find({
  "loves":  ["apple", "carrot"] 
}).sort({
  "weight": 1
}).limit(1)
```
