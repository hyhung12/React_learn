# React_learn

```
<div id = "root"></div>
```
- JSX - syntax extension to write HTML-like code
```
ReactDOM.render(
  <div>
    <h1>Hello World!</h1>
    <p>This is a paragraph.</p>
  </div>,
  document.getElementById("root")
);
```
- expression is put in {} in JSX
- Styling:
```
<h1 className = "heading">Hello World</h1>
<img alt="random.jpg" src="https" />
```
- ReactJS - component-based architecture, each component renders a part of UI
- Components: (can be reused)
```
import React from "react"

function Heading():
return <h1>Hello World</h1>;

export default Heading;
```

- Import/Export:
+ Can rename if using export default
  
```
export default pi;
import pie12 from ./pi.jsx;
```
+ Export multiple items
  
```
export {item1, item2} 
import {item1, item2} from ./components/App
import * as big_item from module1 -> not recommended
```
- Reat props:
+ html attributes <=> React properties (prop)

- React DevTools:
+ To view name of props

- Mapping
```
{notes.map((eachNote) => (
  <Note title12={eachNote.title} content12={eachNote.content} />
))}
```

- Conditional Rendering
hooks can cause a functional component (including the top-level App component) to re-run.

When a hook is used inside a functional component, React internally keeps track of the state changes and re-renders the component whenever the state changes. This can cause the component to re-run from the beginning, including the top-level App function.

Hook: change value of variable and re-render

- Object & Array Destructuring:
```
const [cat, dog] = animals;
||
var cat = animals[0];
var dog = animals[1];
```

- Event Handling:
```
https://www.w3schools.com/tags/ref_eventattributes.asp
```

- when function is called, it can get access to previous value
- function can also be passed as argument (aka callback)
```
function sum(a, b, callback) {
const square = function(x) {
  return x * x;
}

function sum(a, b, callback) {
  const result = a + b;
  return callback(result);
}

const result = sum(2, 3, square);
console.log(result); // Output: 25
```

Destructing - 18
Event handling - 10
Forms - 14
Class & Functional - 6
Complex State - 20

-------- 68

Spread - 11
Component Tree - 23
Keeper 3 - 25

-------- 59

blah blah - 17
```
