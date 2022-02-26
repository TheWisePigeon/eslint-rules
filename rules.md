# Format:
    /* rule */
    ** what the rule actually does **

## Rules that care about how the code looks rather than how it executes 😑
    /* eslint-disable array-bracket-newline */

**enforce linebreaks after opening and before closing brackets**
```javascript
    //error
    let a = [1, 2];
    let b = [];

    //no errors
    let a = [
        1,
        2

    ];
    let b = [

    ];

```

/* eslint-disable array-bracket-spacing */