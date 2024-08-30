# Lesson 10: Multimedia Elements

## Embedding Videos and Audio

HTML provides elements for embedding multimedia content like videos and audio into web pages, enhancing the user experience by offering rich media content.

### Embedding Videos

The `<video>` element is used to embed video files. You can specify multiple sources for different video formats to ensure compatibility across browsers.

- **Basic Syntax**:
  ```html
  <video controls>
      <source src="video.mp4" type="video/mp4">
      <source src="video.ogg" type="video/ogg">
      Your browser does not support the video tag.
  </video>
  ```

- **Attributes**:
  - `controls`: Displays video controls like play, pause, and volume.
  - `autoplay`: Automatically plays the video when the page loads (use cautiously as it can be intrusive).
  - `loop`: Replays the video when it ends.
  - `muted`: Mutes the video by default.

### Embedding Audio

The `<audio>` element is used to embed audio files. Like the `<video>` element, you can provide multiple sources for different audio formats.

- **Basic Syntax**:
  ```html
  <audio controls>
      <source src="audio.mp3" type="audio/mpeg">
      <source src="audio.ogg" type="audio/ogg">
      Your browser does not support the audio tag.
  </audio>
  ```

- **Attributes**:
  - `controls`: Displays audio controls like play, pause, and volume.
  - `autoplay`: Automatically plays the audio when the page loads.
  - `loop`: Replays the audio when it ends.
  - `muted`: Mutes the audio by default.

### Example HTML for Video and Audio

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Embedding Multimedia</title>
</head>
<body>
    <h1>Video Example</h1>
    <video controls width="320" height="240">
        <source src="sample.mp4" type="video/mp4">
        <source src="sample.ogg" type="video/ogg">
        Your browser does not support the video tag.
    </video>

    <h1>Audio Example</h1>
    <audio controls>
        <source src="sample.mp3" type="audio/mpeg">
        <source src="sample.ogg" type="audio/ogg">
        Your browser does not support the audio tag.
    </audio>
</body>
</html>
```

## Using the `<canvas>` Element

The `<canvas>` element is used to draw graphics on a web page via scripting (usually JavaScript). It can be used for rendering graphs, game graphics, or other visual images on the fly.

### Basic Usage

- **Basic Syntax**:
  ```html
  <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
  Your browser does not support the canvas element.
  </canvas>
  ```

- **Drawing on the Canvas**:
  To draw on the canvas, you need to use JavaScript. Here’s a simple example of drawing a rectangle:

  ```html
  <script>
      var canvas = document.getElementById('myCanvas');
      var context = canvas.getContext('2d');
      context.fillStyle = '#FF0000';
      context.fillRect(10, 10, 150, 75);
  </script>
  ```

### Example HTML with Canvas

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Canvas Example</title>
</head>
<body>
    <h1>Canvas Drawing</h1>
    <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
        Your browser does not support the canvas element.
    </canvas>

    <script>
        var canvas = document.getElementById('myCanvas');
        var context = canvas.getContext('2d');
        context.fillStyle = '#FF0000';
        context.fillRect(10, 10, 150, 75);
    </script>
</body>
</html>
```

By understanding how to embed multimedia elements and use the `<canvas>` element, you can create dynamic and interactive web pages that engage users with rich media content.

---

This lesson provides a foundational understanding of multimedia elements in HTML, preparing you for more advanced techniques in web graphics and media integration.

[Next: 11-Accessibility-in-HTML](./11-Accessibility-in-HTML.md)