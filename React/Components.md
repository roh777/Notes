### Components

* Basic building blocks in React.
* Components have:
  * State: State stores the attributes associated with the Component. States can be changed.

  * Props (aka Properties): They are inherited by Component from parent component. They are immutable.

  * LifeCycle: Every component has a LifeCycle, which contains stages like
    1. Component will mount.
    2. Component did mount.
    3. Component recieved Properties.
    4. Component was removed.


#### Things to keep in mind

  * The react components doesn't neccesarily have correspond to a UI object. It can be used to manage a child component, or auxilary component. It can return ReactUI, null, state.

It can return other components
  ```javascript
   render() {
     return <MyOtherComponent />
   }
  ```

It can return function invocations
```javascript
  render() {
    return this.props.children(this.someState)
  }
```

Or can return nothing, manage something as audio.

  ```javascript
    render() {
      return null;
    }
  ```

* If two compoents need to share state, then build on level up compoent to share states using props.
