# 0x03. Sass & Scss

Sass & Scss style development worked in this project.

## Tasks:

### 0. Always debugging!
Sass file that prints `Hello world` in the debug output.

### 1. Color variable
Sass file that assigns the text color to the HTML tags `body` and `p`.

### 2. Colors
Sass file that assigns:<br>
+ Text color to tags `body` and `p`.<br>
+ Background color to tags `body` and `h2`.

### 3. Nested tag
Sass file that assigns:<br>
+ No margin or padding in `body` tags.<br>
+ Margin 10px to all of the `p` tags inside `body` tags.

### 4. Nested class
Sass file that assigns:<br>
+ Text color to elements inside `body` tags.<br>
+ Text color to any elements of class `.red` inside `body` tags.

### 5. Nested child
Sass file that assigns:<br>
+ Text color to elements inside `body` tags.
+ Text color to any elements of class `.red` that are the first children of the `body`.

### 6. Nested hover
Sass file that assigns:<br>
+ Text color to `button` tags.
+ When the user hovers over `button` tags, text color should change.

### 7. Nested and nested again
Sass file that assigns:<br>
+ Font size 14px to all `body` tags.
+ Font size 16px to all `h1` tags inside `body` tags.
+ Font size 12px to `h1` tags of class `.smaller` inside `body` tags.

### 8. Margin mixin
Sass file that assigns:
+ Margin left and right at 10px to `body` tags.
+ Margin left and right at 15px to `div` tags.

### 9. Extended
Sass file that assigns:<br>
+ Font size 12px to all tags of class `.info`
+ Text color to all tags of class `.success` and extend style of the class `.info`.
+ Text color to all tags of class `.warning` and extend style of the class `.info`.

### 10. Import colors
Sass file that assigns:<br>
+ Text color `$red` from `10-colors.scss` to the class `.red`.
+ Text color `$green` from `10-colors.scss` to the class `.green`.
+ Text color `$blue` from `10-colors.scss` to the class `.blue`.

### 11. For each
Sass file that creates a class for each name in the list `$list-names` and assigns the background image based on the name.

### 12. Loop Headers
Sass file that creates `H*` tags, where ‘*’ is the size of the font used.
+ `h1` must have font size equal to 1px, `h2` must have font size equal to 2px, etc.
