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
</script>
