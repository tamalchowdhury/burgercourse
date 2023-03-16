# Burger Receipt

Dev notes:

`https://github.com/tsayen/dom-to-image`

CDN JS embed:

`https://cdnjs.com/libraries/dom-to-image`

Implementation:

```
  domtoimage
    .toJpeg(document.querySelector(".reciept"), { quality: 0.95 })
    .then(function (dataUrl) {
      var link = document.createElement("a");
      link.download = "my-image-name.jpeg";
      link.href = dataUrl;
      link.click();
    });
```

Notes on CSS: Have to update the `.reciept` div's background color to white for it to show up. Otherwise it will render black.

