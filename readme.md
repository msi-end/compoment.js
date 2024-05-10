<p align="center">
  <a href="https://nodemon.io/"><img src="https://user-images.githubusercontent.com/13700/35731649-652807e8-080e-11e8-88fd-1b2f6d553b2d.png" alt="Nodemon Logo"></a>
</p>
<h1 align="center"> Component.js  </h1>

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
         -Or-
<script src="path/to/{var}.{file_name}.js"></script>
```
### Adding Elements
To add an HTML element as a component to your HTML document:

```js
const element = ComponentLibrary.addElement({
    tag: 'div',
    id: 'myDiv',
    class: 'myClass',
    parent: document.body
});
```

### Updating Elements
To update an existing HTML element:
```js
ComponentLibrary.updateElement('myDiv', {
    class: 'newClass',
    style: 'color: red;',
    text: 'New Content'
});
```
### Retrieving Elements
To retrieve an existing HTML element:
```js
const element = ComponentLibrary.getElement('myDiv');
const button = ComponentLibrary.addElement({
    tag: 'button',
    id: 'myButton',
    text: 'Click Me',
    parent: document.body
});
```

### Updating Button Style
```js
ComponentLibrary.updateElement('myButton', {
    class: 'btn btn-primary',
    style: 'background-color: blue; color: white;'
});
```
## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
