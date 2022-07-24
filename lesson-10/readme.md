# Whitespace in HTML

You may have noticed that there is a lot of whitespace in the code examples above. This is entirely optional.
These two lines of code are equivalent:

```html
<p>I love HTML.</p>

<p>I        love
         HTML.</p>
```

When displaying the code, the HTML parser converts each sequence of whitespace to a single space, regardless of how much whitespace you use inside HTML element content (which can comprise one or more space characters, but also line breaks). So, why so much whitespace? The key is readability.

If your code is neatly structured, it may be easier to grasp what is going on. Each nested element in our HTML is indented by two spaces more than the one that sits within. It is up to you to decide on the formatting style (for example, how many spaces for each level of indentation).
