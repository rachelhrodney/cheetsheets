# javascript!

### variables

- `var b = true`: boolean
- `var n = 5`: number
- `var s = "hello"`: String
- `var a = [1, "hello", null]`: Array
- `var o = {key:"value", key2:42}`: Object


### function

```js
// function declaration (creating it)
function hello (arg) {
    console.log(arg)
}

// function call
hello("print me")

// another way to declare a function
ar funk = (arg) => {
    console.log(arg)
}

// as a member of a React class Component:
class Hello extends React.Component{
    funk = () =: {
        console.log(this) // refers to "hello"
    }
}

```

### objects

```js
// key/value pairs
var obj = {
    key:"value" 
}
// uwe dot notation to access a value:
obj.key

//destructuring:
var {key} = obj // now you can use the "key" variable

```

### arrays
```js
var arr = [1,2,"three",null]
//access by the index, (starting with 0):
arr[2] = "three"

//loop:
arr.map((item,index)=>{
    console.log(item, index)
})

//filter
arr.filter((item, index)=>{
    return
})


// sort
arr.sort((abb)=>{
    //return a negative number, a postive number, or zero
    return a - b
})

//add an item to an array:
arr.push("new item")

//concatenate two arrays:
arr.concat(arr2)

//take a sub-array
arr.splice(0, 10)
```

### conditional statements
```js
var n = 5
if(n == 5){
    console.log("YAY ITS TRUE!")
}
// you can use >, <, !==
```