# react !

### Component

**class component:**
```js
class Thingy extends REact.Component {
    
    state={
        text:'hello'
    }

    render() {
        return (<div>
            {this.state.text}
            <LittleThingy name={this.state.text}
                chanteText={text=> this.setState({text})}
            />
        )</div>
    }
}
```

Now you can change state with"
``` js
this.setState({text: ''})
```

**function component**
```js
function LittleThingy() {
    return <div style={{height:40}} onClick={()=>props.hangetText('newText')}>              {props.name}
    </div>
}
```

To use a component:
```js
<LittleThingy name="rachel" />
```

Props can be anyting, a string, a number, or even a function!