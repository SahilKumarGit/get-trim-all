# get-trim-all


```bash
npm install get-trim-all
```

```js
const trimAll = require('get-trim-all')
```

```js
// Helloworld 
let str = ' Helloworld '

console.log(trimAll(str)) // 'helloworld'
```

```js
let arr = [' google ', ' facebook ']

console.log(trimAll(arr)) // ['google', 'facebook']
```

```js
let obj = {
  name: ' Sahil Kumar ',
  age: 19,
  hobbies: [' programming ', ' badminton ']
}

console.log(trimAll(obj)) // { name: 'Sahil Kumar', age: 19, hobbies: ['programming', 'badminton'] }
```

```js
let arr = [
  { city: [' bbsr ', ' ctc '] }
]

console.log(trimAll(arr)) // [{ city: ['bbsr ', 'ctc']}]
```

```js
let obj = { ' name ': ' sahil   Kumar ' }
console.log(trimAll(arr, true)) // { ' name ': 'sahil   Kumar' }
```