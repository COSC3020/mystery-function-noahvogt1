# Mystery Function
I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

I did not use any reasources

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

ANSWER: It recursively finds the maximum number in an array. Testing edge cases if there is only an array size one and then recursively runs down the array and back up to find the greatest number.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```
