# lib_GcdCalculator
Author: [@javascriptjp](https://github.com/javascriptjp)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/K3K1AQ3A3)

## How to use?

```javascript
function gcd() {
    let[g,j,...s]=[(a,b)=>b?g(b,a%b):a,...arguments]
    for(const t of s)j=g(j,t); 
    return j;
}
```

```
console.log(gcd(400,600))
console.log(gcd(400,600,200))
```
