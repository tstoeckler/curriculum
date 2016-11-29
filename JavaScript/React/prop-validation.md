# Prop Validation
author: catalin

levels:

  - basic

  - advanced

  - medium

type: normal

category: best practice

links:

  - >-
    [facebook.github.io](https://facebook.github.io/react/docs/reusable-components.html#prop-validation){website}

---
## Content

JavaScript being a loosely typed language you can experience runtime errors when you expect data of one type but receive another. *React* helps us in this by providing a feature called `propTypes`.

This helps you in validating if the data (`props`) received in components is valid compared to what you expect. If not, warnings will be displayed in the *JavaScript* console.

All validators are available through `React.PropTypes` and should be specified as part of your *React* component, on the property `propTypes`:
```jsx
React.createClass({
  propTypes: {
    myArray: React.PropTypes.array,
    myBoolean: React.PropTypes.bool,
    myFunction: React.PropTypes.func,
    myNumber: React.PropTypes.number,
    myObject: React.PropTypes.object,
    myString: React.PropTypes.string,
  },
  // other code
});

```

The validations above state that the specified `props` should be **JS** primitives. By default, they are **optional** so no warnings are shown if they are not passed to the component, they can be required by adding `isRequired` to the type like `React.PropTypes.string.isRequired`.

Note that `propTypes` are checked only in development mode due to performance reasons.

---
## Practice

Complete the missing validation such that the first prop is a function and the second an object:

```jsx
propTypes: {
  myFunction = React.???.???,
  myObject = React.PropTypes.???,
},
```

* `PropTypes`
* `func`
* `object`
* `function`
* `obj`
* `node`
* `element`
* `method`
* `Props`
* `Primitives`

---
## Revision

Complete the missing validation such that the first prop is a function and the second an object:

```jsx
propTypes: {
  myFunction = React.???.???,
  myObject = React.PropTypes.???,
},
```

* `PropTypes`
* `func`
* `object`
* `function`
* `obj`
* `node`
* `element`
* `method`
* `Props`
* `Primitives`