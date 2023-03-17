# Burger Reciept

## DOM to Image

Link to your HTML:

https://cdnjs.com/libraries/dom-to-image

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/dom-to-image/2.6.0/dom-to-image.min.js" integrity="sha512-01CJ9/g7e8cUmY0DFTMcUw/ikS799FHiOA0eyHsUWfOetgbx/t6oV4otQ5zXKQyIrQGTHSmRVPIgrgLcZi/WMA==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```

DOM to image repository:

https://github.com/tsayen/dom-to-image

Download an jpeg image function:

```js
domtoimage
    .toJpeg(document.querySelector(".reciept"), { quality: 0.95 })
    .then(function (dataUrl) {
      var link = document.createElement("a");
      link.download = "my-image-name.jpeg";
      link.href = dataUrl;
      link.click();
    });
```