# Draggable Background

A jQuery plugin to make background images draggable.

## Configuration
<table>
  <tr>
    <th>Option</th>
    <th>Type</th>
    <th>Known Values</th>
    <th>Default Value</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>bound</td>
    <td>Boolean</td>
    <td>true|false</td>
    <td>true</td>
    <td>Whether dragging is bounded by the edges of the image.</td>
  </tr>
  <tr>
    <td>axis</td>
    <td>String</td>
    <td>x|y</td>
    <td></td>
    <td>If specified, restrict dragging along x or y axis.</td>
  </tr>
  <tr>
    <td>beforeDrag</td>
    <td>Function</td>
    <td>function($element) {}</td>
    <td></td>
    <td>Called before the mouse starts dragging.</td>
  </tr>
  <tr>
    <td>onDrag</td>
    <td>Function</td>
    <td>function($element) {}</td>
    <td></td>
    <td>Called when the background is being dragged.</td>
  </tr>
  <tr>
    <td>finishDrag</td>
    <td>Function</td>
    <td>function($element) {}</td>
    <td></td>
    <td>Called when the mouse is released from dragging.</td>
  </tr>
</table>

## Usage
```js
// default options
$('div').backgroundDraggable()

// only draggable in the x direction, and dragging is not bounded by the image
$('div').backgroundDraggable({ bound: false, axis: 'x' })
```

## Demo
http://kentor.github.com/jquery-draggable-background/

## Changelog

v1.1 [2013-05-19]
- Touch support.

v1.0 [2012-09-23]

- Initial release.

## License

Copyright (c) 2012 Kenneth Chung

Licensed under the [MIT](http://www.opensource.org/licenses/mit-license.php) license.
