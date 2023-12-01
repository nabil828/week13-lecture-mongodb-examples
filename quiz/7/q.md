How to update all unicorn genders to "unknown"?


Options

A.
```js
db.unicorns.update({}, 
  {$set: 
    {gender: "unknown"}
  },
  {multi: true}
)
```

B.
```js
db.unicorns.update({}, 
  {gender: "unknown"}
  ,
  {multi: true}
)
```

C.
```js
db.unicorns.update({}, 
  {$set: 
    {gender: "unknown"}
  }
)
```

D.
```js
db.unicorns.update({}, 
  {gender: "unknown"}
  ,
  {multi: true}
)
```