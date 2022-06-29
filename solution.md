## Return Negative

```js

function makeNegative(num) {
  num = Math.abs(num) * -1
  return num
}
// source: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/abs

```

## Sum of Positive

```js

function positiveSum(arr) {
  let sum = 0
  for (let i = 0; i < arr.length; i++) {
    if(arr[i] > 0) sum += arr[i];
  }
  return sum
}

```

## Function 2

```js

function square(num) {
  num = num*num
  return num
}

```

## Sum Arrays

```js

function sum (numbers) {
  let sum = 0
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum
};

```

## Reversed Strings

```js

function solution(str){
  str = [...str].reverse().join("")
  return str
}
// source: https://stackabuse.com/how-to-reverse-a-string-in-javascript/

```
