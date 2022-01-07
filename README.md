- [Structure](#structure)
    + [Page structure](#page-structure)
    + [Headings](#headings)
    + [Comment](#comment)
- [Separators](#separators)
    + [Line Break](#line-break)
    + [Horizontal Rule](#horizontal-rule)
    + [Paragraph](#paragraph)
- [Lists](#lists)
    + [Ordered lists](#ordered-lists)
    + [Unordered lists](#unordered-lists)
    + [Nested lists](#nested-lists)
- [Media](#media)
    + [Link](#link)
    + [Image](#image)
    + [Audio](#audio)
    + [Video](#video)
- [Containers](#containers)
    + [Header](#header)
    + [Footer](#footer)
    + [Section](#section)
    + [Span](#span)
    + [Div](#div)
- [Style](#style)
    + [Bold](#bold)
    + [Italic](#italic)
    + [Small](#small)
- [Inputs](#inputs)
    + [Form](#form)
    + [Button](#button)
- [Attributes](#attributes)
    + [Class](#class)
    + [IDs](#ids)




# Structure

### Page structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Cheatsheet</title>
</head>
<body>
  
</body>
</html>
```

### Headings
```html
<h1>
  HTML
</h1>
<h2>
  HTML
</h2>
<h3>
  HTML
</h3>
<h4>
  HTML
</h4>
<h5>
  HTML
</h5>
<h6>
  HTML
</h6>
```

### Comment
```html
<!-- this is a comment -->
```

# Separators

### Line Break
```html
The quick, brown fox <br />
jumps over <br />
a lazy dog.
```

### Horizontal Rule
```html
Far far away,
<hr />
behind the word mountains,
<hr />
far from the countries Vokalia and Consonantia,
<hr />
there live the blind texts.
```

### Paragraph
```html
<p>
  A wizard’s job is to vex chumps quickly in fog.
</p>
```

# Lists 

### Ordered lists
```html
<ol>
  <li>
    fox
  </li>
  <li>
    cat
  </li>
  <li>
    dog
  </li>
  <li>
    rabbit
  </li>
</ol>
```

### Unordered lists
```html
<ul>
  <li>
    rabbit
  </li>
  <li>
    fox
  </li>
  <li>
    cat
  </li>
  <li>
    dog
  </li>
</ul>
```

### Nested lists 
```html
<ul>
  <li>Wolf</li>
  <li>Fox</li>
  <li>
    <strong>Bird</strong>
    <br />
    <ul>
      <li>Duck</li>
      <li>Chicken</li>
      <li>Turkey</li>
    </ul>
  </li>
</ul>
```

# Media

### Link
```html
<a href="https://github.com/Ladydiana/HTMLCheatsheet" target="_blank" title="HTML Cheatsheet">HTML Cheatsheet</a>
```

### Image
```html
<img src="https://cdn.britannica.com/q:60/91/181391-050-1DA18304/cat-toes-paw-number-paws-tiger-tabby.jpg" alt="Polydactyl kitty" width="600" />
```

### Audio
```html
<audio controls src="https://upload.wikimedia.org/wikipedia/commons/6/62/Meow.ogg"></audio>
```

### Video
```html
<video src="https://www.youtube.com/watch?v=My2puqWOVqw" controls></video>
```

# Containers

### Header
```html
<header class="page-header">
    <h1>Grouping the intro. No styling.</h1>
</header>
```

### Footer
```html
<footer>
    <p>Footer info (Copyright, Author, Year, etc.). No styling.</p>
</footer>
```

### Section
```html
<section class="html-information">
    <h2>Pangram</h2>
    <p>The quick, brown fox jumps over a lazy dog.</p>
</section>
```

### Span
```html
<span class="class-1">Let's keep this in a class for easy formatting.</span>
```

### Div
```html
<div class="class-2">Let's also keep this in a class for easy formatting.</div>
```

# Style

### Bold
```html
<strong>This is bold text.</strong>
```

### Italic
```html
<em>This is italic text.</em>
```

### Small
```html
<small>This is smaller text.</small>
```

# Inputs

### Form
```html
<form>
    <label for="name">Name: </label>
    <input type="text" name="name" id="name" required>
    <label for="email">Email: </label>
    <input type="email" name="email" id="email" required>
    <input type="submit" value="Subscribe to our newsletter!">
</form>
```

### Button
```html
<button class="button1">
  Login!
</button>
```

# Attributes

### Class
```html
<a href="https://github.com/Ladydiana" class="css-git-repo-url">Github</a>
```


### IDs
```html
<a href="https://github.com/Ladydiana" id="js-git-repo-url-id">Github</a>
```