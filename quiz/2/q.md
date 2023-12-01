What does the following query return?

```js
db.unicorns.find({
  "loves": "grapes",
  "weight": { $lt: 700 }
})
```

Options

A.
```
Find the unicorns that love grapes and weigh less than 700 pounds.
```

B.
```
Find the unicorns that love grapes and weigh more than 700 pounds.
```

C.
```
Find the unicorns that love grapes or weigh less than 700 pounds.
```

D.
```
Find the unicorns that love grapes or weigh more than 700 pounds.
```