# Format:
/*eslint-disable rule */
** what the rule actually does **
Quick illustration

## Rules that care about how the code looks rather than how it executes 😑
```javascript
/* eslint-disable array-bracket-newline */
```


**enforce linebreaks after opening and before closing brackets**
```javascript
    //error-prone
    let a = [1, 2];
    let b = [];

    //clean code
    let a = [
        1, 2

    ];
    let b = [

    ];

```

```javascript
/* eslint-disable array-bracket-spacing */
```

**enforce consistent spacing inside array brackets**
```javascript
    //error-prone code
    let a = [ 'some', 'value'];
    let b = ['some', 'value' ];

    //clean code
    let a = [ 'some', 'value' ];
    let b = [ 'another', 'value' ]
```

```javascript
/* eslint-disable array-element-newline */
```
**enforce line breaks after each array element**
```javascript
    //error-prone code
    let a = [1];
    let b = [2, 3];
    let c = [4, 5, 6];
    let d = [
        1, 2, 3
    ];

    //clean code
    let a = [
        1
    ];
    let b = [
        2,
        3
    ];
```

```javascript
/* eslint-disable brace-style */
```
**enforce consistent brace style for blocks. Read more about [brace style](https://en.wikipedia.org/wiki/Indent_style)**
```javascript

```