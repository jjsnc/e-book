<template>
  <div>home</div>
</template>

<script>
console.log([1, 2, 3].map((x) => x * x));

var obj = {
  p: [
    "Hello",
    {
      y: "World",
    },
  ],
};

var {
  p: [x, { y }],
} = obj;

console.log(x, y);

export default {
  name: "about",
};


let arrayLike = {
  '0':'a',
  '1':'b',
  '2':'c',
  'length':'3',
}


var arr1 = [].slice.call(arrayLike)

console.log(arr1,'arr1')

let arr2 = Array.from(arrayLike)

console.log(arr2);


</script>
