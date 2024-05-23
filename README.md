# JAVASCRIPT


#### Variables
- **var**: Reassignable and redeclarable.
- **let**: Block-scoped, reassignable.
- **const**: Immutable once assigned.

#### Example
```javascript
var x = 1;
if (x === 1) {
    var x = 2;
    console.log(x); // 2
}
console.log(x); // 2
```

#### Datatypes
- **Number**: Numeric values (`var x = 10;`)
- **String**: Characters in quotes (`var x = "text";`)
- **Boolean**: `true` or `false`
- **Null**: Represents no value (`var x = null;`)
- **Undefined**: Declared but not assigned (`let x;`)
- **Object**: Collection of key-value pairs
- **Array**: Stores multiple values
- **Function**: Block of code executed on call

#### Example
```javascript
let str = "hello";
console.log(str); // hello
```

#### Operators
- **Arithmetic**: `+`, `-`, `*`, `/`, `%`, `++`, `--`
- **Comparison**: `==`, `===`, `!=`, `>`, `<`, `>=`, `<=`
- **Bitwise**: `&`, `|`, `^`, `~`, `<<`, `>>`, `>>>`
- **Logical**: `&&`, `||`, `!`
- **Assignment**: `=`, `+=`, `-=`, `*=`, `/=`, `%=`

#### Example
```javascript
let x = 5;
let y = 3;
console.log(x + y); // 8
```
