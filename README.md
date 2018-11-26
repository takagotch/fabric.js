### fabric.js
---
https://github.com/fabricjs/fabric.js

http://fabricjs.com/docs/
```
bower install fabric
npm install fabric --save
node build.js
node build.js modules=text,serialization,parser
node build.js modules=text
node build.js modules=parser,text
node build.js modules=interaction
node build.js modules=ALL
node build.js modules=ALL exclude=gestures,image_filters
node build.js modules=... minifier=yui
node build.js modules=... minifier=closure
node build.js requirejs modules=...
node build.js sourcemap modules=...

npm run lint && npm run lint_tests
npm install
npm install -g testem
testem

node build.js modules=ALL exclude=json no-strict no-svg-export
```

```
//# sourceMappingURL=fabric.min.js.map
```

```
<!DOCTYPE html>
<html>
<head>
</head>
<body>
  <canvas id="canvas" width="300" height="300"></canvas>
  <script src="lib/fabric.js"></script>
  <script>
    var canvas = new fabric.Canvas('canvas');
    var rect = new fabric.Rect({
      top : 100,
      left : 100,
      width : 60,
      height: 70,
      fill : 'red'
    });
    canvas.add(rect);
  </script>
</body>
</html>
```


