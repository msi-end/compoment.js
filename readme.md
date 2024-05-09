# Component.js

This is a minimalistic and simple component library designed to facilitate adding, updating, and retrieving HTML elements easily in your web projects.

## Features

- Add HTML elements as components to your HTML documents effortlessly.
- Update elements with ease using intuitive methods.
- Retrieve elements and update them dynamically.

## Installation

You can include the library directly into your HTML document:

```html
<script src="path/to/component.js"></script>
<script src="path/to/html.elements.js"></script>
```
### Adding Elements
To add an HTML element as a component to your HTML document:

```
javascript
Copy code
const element = ComponentLibrary.addElement({
    tag: 'div',
    id: 'myDiv',
    class: 'myClass',
    parent: document.body
});
```

### Updating Elements
To update an existing HTML element:
```
javascript
Copy code
ComponentLibrary.updateElement('myDiv', {
    class: 'newClass',
    style: 'color: red;',
    text: 'New Content'
});
```
### Retrieving Elements
To retrieve an existing HTML element:
```
javascript
Copy code
const element = ComponentLibrary.getElement('myDiv');
Examples
Adding a Button
javascript
Copy code
const button = ComponentLibrary.addElement({
    tag: 'button',
    id: 'myButton',
    text: 'Click Me',
    parent: document.body
});
```

### Updating Button Style
```
javascript
Copy code
ComponentLibrary.updateElement('myButton', {
    class: 'btn btn-primary',
    style: 'background-color: blue; color: white;'
});
```
## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
