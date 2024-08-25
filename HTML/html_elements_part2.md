
## 3. Media Elements

### `<img>`
Embeds an image.

```html
<img src="image.jpg" alt="A beautiful scenery" width="500" height="600">
```

### `<audio>`
Embeds sound content.

```html
<audio controls>
  <source src="sound.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

### `<video>`
Embeds video content.

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

### `<source>`
Specifies multiple media resources for media elements like `<video>` and `<audio>`.

```html
<video controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```

### `<figure>`
Specifies self-contained content, like illustrations, diagrams, photos, etc.

```html
<figure>
  <img src="image.jpg" alt="A beautiful scenery">
  <figcaption>An image with a caption</figcaption>
</figure>
```

### `<figcaption>`
Defines a caption for a `<figure>` element.

```html
<figure>
  <img src="image.jpg" alt="A beautiful scenery">
  <figcaption>This is a caption for the image.</figcaption>
</figure>
```

## 4. Form Elements

### `<form>`
Defines an HTML form for user input.

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <input type="submit" value="Submit">
</form>
```

### `<input>`
Defines an input field.

```html
<input type="text" name="username" placeholder="Enter your name">
```

### `<textarea>`
Defines a multiline text input control.

```html
<textarea name="message" rows="5" cols="30">
  Enter your message here.
</textarea>
```

### `<button>`
Defines a clickable button.

```html
<button type="button">Click Me!</button>
```

### `<select>`
Defines a dropdown list.

```html
<select name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
</select>
```

### `<option>`
Defines an option in a dropdown list.

```html
<select name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
</select>
```

### `<label>`
Defines a label for an `<input>` element.

```html
<label for="username">Username:</label>
<input type="text" id="username" name="username">
```

### `<fieldset>`
Groups related elements in a form.

```html
<fieldset>
  <legend>Personal Information</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname">
</fieldset>
```

### `<legend>`
Defines a caption for a `<fieldset>`.

```html
<fieldset>
  <legend>Account Information</legend>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">
</fieldset>
```
