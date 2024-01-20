try to test time for scrollIntoView method using repeated action method.

```
const px1000 = result.reduce( (a,b)=>{return a+b;}, 0 )/result.length;
undefined
const precentage = (px1000 / 1000); // precentage to calcuate based on scroll pixel for example scroll 127.32 pixel = (precentage * 127.32)
undefined
const px10000 = 10000 * precentage;
undefined
px10000
3160.125413293809 // 10000 pixel time
```

final result was: 316.0125413293809 milliseconds 
