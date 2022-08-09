# Nesting elements

Elements can be nested inside of other elements. This is known as nesting. If you wish to say that you want to be a HTML Developer **so bad**, you could surround the word _so bad_ in a `<strong>` element, which indicates that the word will have strong(er) text wording:

```html
<p>When I grow up, I want to be a HTML Developer <strong>so bad</strong>.</p>
```

Nesting can indeed be done correctly or incorrectly. In the above example, we opened the `p` element first, followed by the `strong` element. To ensure appropriate nesting, we should close the `strong` element first, followed by closing the `p`.

An example of incorrect nesting:

```html
<p>When I grow up, I want to be a HTML Developer <strong>so bad.</p></strong>
```

> ℹ️ The tags should open and end in such a way that they are either inside or outside of one another. With the type of overlap seen in the preceding example, the browser must guess at your intention. This type of guesswork might lead to unexpected outcomes.
