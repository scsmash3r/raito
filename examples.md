# Examples
## Blockquotes
Markdown
```markdown
> Not all those who wander [are lost](README)
```

Output
> Not all those who wander [are lost](README)

## Tables
Markdown
```markdown
| Ingredient    | Quantity      | Price  |
| ------------- |---------------|--------|
| Milk          | 1L            | $5     |
| Flour         | 350g          | $2     |
| Eggs          | 6             | $6.50  |
```

Output
| Ingredient    | Quantity      | Price  |
| ------------- |---------------|--------|
| Milk          | 1L            | $5     |
| Flour         | 350g          | $2     |
| Eggs          | 6             | $6.50  |

## Checklists
Markdown
```markdown
- [x] Beer
- [ ] Pancakes
```

Output
- [x] Beer
- [ ] Pancakes

## Lists
Markdown
```markdown
- Frodo Baggins
- Gandalf the Grey
```

Output
- Frodo Baggins
- Gandalf the Grey

## Code Blocks
Markdown
````markdown
```ts
class MyClass {
  public static myValue: string;
  constructor(init: string) {
    this.myValue = init;
  }
}
import fs = require("fs");
module MyModule {
  export interface MyInterface extends Other {
    myProperty: any;
  }
}
declare magicNumber number;
myArray.forEach(() => { }); // fat arrow syntax
```
````
Output
```ts
class MyClass {
  public static myValue: string;
  constructor(init: string) {
    this.myValue = init;
  }
}
import fs = require("fs");
module MyModule {
  export interface MyInterface extends Other {
    myProperty: any;
  }
}
declare magicNumber number;
myArray.forEach(() => { }); // fat arrow syntax
```
## Links
Markdown
```markdown
[Here's a link](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
```
Output

[Here's a link](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
