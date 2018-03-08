# nya.js
Binding custom events when a variable changes.

# Installation
npm install --save nya.js
# Usage

## es6+
    import { Nya } from 'nya.js';

## node.js
Forthcoming support
## cdn
Forthcoming support

# Example

    Nya.bing("name", ()=>{
      console.log("The value of variable 'name' changes to  :" + Nya.name)
    })

    console.log(Nya.name)
    // null

    Nya.name = "example"
    // The value of variable 'name' changes from null to 'example'
