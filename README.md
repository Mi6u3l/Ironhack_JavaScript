![Ironhack](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_6e171edc323b4df30ae1f1cefe63c7e2.png)

JavaScript
====================================


Time to practice
-----------------------------
```javascript
var language = prompt('Please select a language');

if (language === 'portuguese') {
  console.log('Olá mundo!');
} else if (language == 'french') {
  console.log('Bonjour tout le monde');
} else {
  console.log('Hello, world!');
}
```

```javascript
var language = prompt('Please select a language');
switch(language) {
  case 'portuguese':
    console.log('Olá mundo!')
  break;
  case 'french':
    console.log('Bonjour tout le monde');
  break;
  default: 
    console.log('Hello, world!');
}
```


```javascript
var i = 1;
while (i <= 30) {
  console.log(i);
  i = i + 1;
}
```

```javascript
var i = 1;
while (i <= 30) {
  if (i === 10) {
    console.log('Ten')
  } else if (i === 20) {
    console.log('Twenty')
  } else {
    console.log(i);
  }
  i = i + 1;
}
```

```javascript
for(var i = 1; i<=30; i++) {
  console.log(i);
}
```


```javascript
for(var i = 1; i<=30; i++) {
   if (i === 10) {
    console.log('Ten')
  } else if (i === 20) {
    console.log('Twenty')
  } else {
    console.log(i);
  }
}
```

