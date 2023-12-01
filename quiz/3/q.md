What does the following query return?

```js
db.unicorns.find({
  "dob": { $gt: new Date("1995") },
  "gender": "m"
}).
```


Options

A.
```
Find the male unicorns born after the year 1995.
```

B.
```
Find the male unicorns born before the year 1995.
```

C.
```
Find male unicorns or unicorns born after the year 1995.
```

D.
```
Find male unicorns or unicorns born before the year 1995.
```