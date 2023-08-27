# MindScript (Templates)

*Pre-trained templates for mindscript*

### How to use ?

**Example:**

```js
const Mind = require("mindscript");
const mind = new Mind('@mindlearn/models/train/en.json');

let input1 = 'What is the capital of France ?';

console.log(`[JohnDoe]: ${mind.think(input)}`); 
```

**Output:**

```
[JohnDoe]: (...)
```