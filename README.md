# all-trim


```bash
npm install get-trim-all
```

```js
const trimAll = require('get-trim-all')
```

```js
// Hello 
let str = ' Hello '

console.log(trimAll(str)) // 'hello'
```

```js
let arr = [' apple ', ' orange ']

console.log(trimAll(arr)) // ['apple', 'orange']
```

```js
let obj = {
  name: ' zhang ',
  age: 19,
  hobbies: [' programming ', ' badminton ']
}

console.log(trimAll(obj)) // { name: 'zhang', age: 19, hobbies: ['programming', 'badminton'] }
```

```js
let arr = [
  { city: [' bbsr ', ' ctc '] }
]

console.log(trimAll(arr)) // [{ city: ['bbsr ', 'ctc']}]
```

```js
let obj = { ' name ': ' zhang ' }
console.log(trimAll(arr, true)) // { ' name ': 'zhang' }
```