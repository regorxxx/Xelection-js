<p align="center">
  <a href="https://regorxxx.github.io/Xelection-js"><img alt="XelectionJS" src="./logo.png" width="150px"></a>
</p>
<p align="center">
  A lightweight javascript library which provides users with a set of options in the form of a small popover over the selected portion of text.
  <br>
  Based on <a href="https://github.com/prateekkalra/Selection-js" target="_"></i>Selection.js</a>.
</p>  

 <p align="center">
  <a href="https://regorxxx.github.io/Xelection-js" target="_">Live Demo</a>
</p>

## Usage

To get started with Xelection.js, download the [Script](https://raw.githubusercontent.com/regorxxx/Xelection-js/master/xelection.min.js) and add it to your project


### Basic

```html
<script src="xelection.min.js"></script>
<script>
  var selection = new Selection();
  selection.init();
</script>
```

### Advanced

```html
<script src="sxelection.min.js"></script>
<script>
  var selection = new Selection();
  selection.config({
    facebook: true,
    twitter: true,
    search:true,
    copy:true,
    speak:false,
    translate: true,
    dictionary: true,
    image: true,
    map: false,
    github: false,
    email: false,
    print: true,
    backgroundColor: '#dc143c', // Crimson
    iconColor: '#ffffff', // White
    opacity: 1,
    scale: 1
  }).init();
</script>
```

# Result

![xelection](https://user-images.githubusercontent.com/83307074/174141344-6af77e12-085b-4f1f-a68d-d7a932cec0db.gif)
