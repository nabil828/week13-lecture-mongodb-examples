What does the following query return?

```js
db.unicorns.find({
  gender: "f",
  weight: { $gt: 600 }
})
```

Options

A.
```
Find the female unicorns weighing over 600 pounds.
```

B.
```
Find the female unicorns weighing under 600 pounds.
```

C.
```
Find female unicorns or unicorns weighing over 600 pounds.
```

D.
```
Find female unicorns or unicorns weighing under 600 pounds.
```