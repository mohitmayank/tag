# tag
> Library for creating DOM elements

### Installation
```shell
bower install tag --save
```

```shell
npm install d-tag --save
```

```html
<script src="tag.js"></script>
```
## `tag(name, *attributes, children)`
* **Parameters**
    - **name**: String  
    - **attributes**: Object (optional)
    - **children**: Array | String
*  **Returns** - HTMLElement

### Example

```js
tag('div', { id: 'content' }, 'content')

tag('div', { id: 'content' }, [
  tag('span', 'content')
])

tag('div', [
  tag('span', '<strong>content</strong>')
])
```

### Release History
- 0.2.0 Removed namespaces
- 0.1.0 Changed npm package name
- 0.0.6 Published package to https://www.npmjs.com/ (name **d-tag**)
- 0.0.5 Added support CommonJS