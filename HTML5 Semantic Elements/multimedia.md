

### **Multimedia**

HTML5 introduced new elements to handle multimedia content such as videos and audio, improving how media is embedded and controlled on web pages.

#### **1. Embedding Videos: `<video>` Tag**
The `<video>` tag is used to embed video content in a webpage. It supports various video formats and provides controls for playback.

```html
<video width="640" height="360" controls>
    <source src="movie.mp4" type="video/mp4">
    <source src="movie.ogg" type="video/ogg">
    Your browser does not support the video tag.
</video>
```

- `width` and `height`: Define the dimensions of the video player.
- `controls`: Adds playback controls (play, pause, volume).
- `<source>`: Specifies multiple video formats to ensure compatibility across different browsers.

#### **2. Embedding Audio: `<audio>` Tag**
The `<audio>` tag is used to embed audio content in a webpage. It supports various audio formats and provides controls for playback.

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    <source src="audio.ogg" type="audio/ogg">
    Your browser does not support the audio element.
</audio>
```

- `controls`: Adds playback controls (play, pause, volume).
- `<source>`: Specifies multiple audio formats to ensure compatibility across different browsers.

---

### **Full Example**

Here’s a complete example combining semantic elements and multimedia:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Semantic Elements</title>
</head>
<body>
    <header>
        <h1>My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to My Website</h2>
        <p>This is a section with an introductory paragraph.</p>
    </section>

    <article>
        <h2>Latest News</h2>
        <p>This is a news article. It contains important content that can be read independently.</p>
    </article>

    <section id="media">
        <h2>Multimedia</h2>

        <h3>Video Example</h3>
        <video width="640" height="360" controls>
            <source src="movie.mp4" type="video/mp4">
            <source src="movie.ogg" type="video/ogg">
            Your browser does not support the video tag.
        </video>

        <h3>Audio Example</h3>
        <audio controls>
            <source src="audio.mp3" type="audio/mpeg">
            <source src="audio.ogg" type="audio/ogg">
            Your browser does not support the audio element.
        </audio>
    </section>

    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
        <p><a href="mailto:info@mywebsite.com">Contact Us</a></p>
    </footer>
</body>
</html>
```

This example demonstrates the use of semantic HTML5 elements to structure content and the integration of multimedia elements for video and audio playback.
```