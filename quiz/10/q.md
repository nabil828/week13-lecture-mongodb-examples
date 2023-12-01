How to count the number of female unicorns older than 30 years.


Options

A.
```js
db.unicorns.find({
  "dob": { $lt: new Date("1987") },
}).count()
```

B.
```js
db.unicorns.find({
  "dob": { $gt: new Date("1987") },
}).count()
```

C.
```js
db.unicorns.find({
  "dob": { $lt: new Date("1987") },
})
```

D.
```js
db.unicorns.find({
  "dob": { $gt: new Date("1987") },
})
```
