# THREE.MapControls

> **NOTE:** This project is deprecated. Use `THREE.OrbitControls` instead, which supports a horizontal panning mode.

Modifications to THREE.TrackballControls, offering camera controls suitable for flat scenes — panning, zooming, and limited rotation.

## Quick Start

Add `MapControls.js` to your project, or install with Bower:

```
bower install --save three.map-controls
```

To use the camera controls:

```javascript
// Setup
var controls = new THREE.MapControls(camera, renderer.domElement, );
controls.surface = new THREE.Plane(new THREE.Vector3(0, 1, 0), 0);

// Update
function update () {
    controls.update();
    
    // ... more updates ...
}
```

## License

The MIT License (MIT)

Copyright (c) 2015 Don McCurdy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
