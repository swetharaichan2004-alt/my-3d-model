GitHub repo la **index.html** create pannunga. Indha coding paste pannunga:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My 3D Model</title>
  <script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/4.3.1/model-viewer.min.js"></script>

  <style>
    body {
      margin: 0;
      background: #111;
    }

    model-viewer {
      width: 100%;
      height: 100vh;
      background: #f5f5f5;
    }
  </style>
</head>

<body>
  <model-viewer
    src="black anton glb (1).glb"
    alt="3D Model"
    camera-controls
    auto-rotate
    ar
    shadow-intensity="1">
  </model-viewer>
</body>
</html>
```

File name exactly **index.html** nu save pannunga.
