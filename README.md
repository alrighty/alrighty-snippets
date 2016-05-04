# alrighty-snippets package

React ES6 snippets for [Atom](https://atom.io).

---

# Snippets

### New component

##### Prefix: _rnc

```js
import React, { Component, PropTypes } from 'react';

export default class ${1:MyComponent} extends Component {
	static propTypes = {

	};

	render() {
		return (
			${2:<div>MyComponent</div>}
		);
	}
}
```
---

### Lifecycle Methods
##### Prefix: _rcwm

```js
componentWillMount() {
	${1}
}
```

##### Prefix: _rcdm

```js
componentWillReceiveProps() {
	${1}
}
```

##### Prefix: _rcwu

```js
componentWillUnmount() {
	${1}
}
```
---

### PropTypes

#### String

##### Prefix: _rps

```js
${1:myProp}: PropTypes.string,
```

##### Prefix: _rpsr

```js
${1:myProp}: PropTypes.string.isRequired,
```

#### Number

##### Prefix: _rpn

```js
${1:myProp}: PropTypes.number,
```

##### Prefix: _rpnr

```js
${1:myProp}: PropTypes.number.isRequired,
```

#### Object

##### Prefix: _rpo

```js
${1:myProp}: PropTypes.object,
```

##### Prefix: _rpor

```js
${1:myProp}: PropTypes.object.isRequired,
```

#### Array

##### Prefix: _rpa

```js
${1:myProp}: PropTypes.array,
```

##### Prefix: _rpar

```js
${1:myProp}: PropTypes.array.isRequired,
```

#### Bool

##### Prefix: _rpb

```js
${1:myProp}: PropTypes.bool,
```

##### Prefix: _rpbr

```js
${1:myProp}: PropTypes.bool.isRequired,
```

#### Element

##### Prefix: _rpe

```js
${1:myProp}: PropTypes.element,
```

##### Prefix: _rper

```js
${1:myProp}: PropTypes.element.isRequired,
```

#### Function

##### Prefix: _rpf
```js
${1:myProp}: PropTypes.func,
```

##### Prefix: _rpfr
```js
${1:myProp}: PropTypes.func.isRequired,
```
