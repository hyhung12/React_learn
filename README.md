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




mapping - 10
map,filter,reduce - 20
arrow - 10
keeper 2 - 10
Conditional - 19

-------- 70

State - 10
Hooks - 18
Destructing - 18
Event handling - 10
Forms - 14
Class & Functional - 6
Complex State - 20

-------- 76

Spread - 11
Component Tree - 23
Keeper 3 - 25

-------- 59

blah blah - 17
