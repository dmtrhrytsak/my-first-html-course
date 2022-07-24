# Single or double quotes?

You might have noticed that the attributes are wrapped in double quotes. However, single quotes may appear among certain HTML code. This is purely a question of taste. You are free to select the one you want. These two lines are interchangeable:

```html
<a href="https://www.html-is-not-a-programming-language.com">Why not?</a>

<a href="https://www.html-is-not-a-programming-language.com">:(</a>
```

Be careful not to combine single and double quotations. The below example demonstrates how to combine quotations incorrectly:

```html
<a href="https://www.example.com'>A super simple link.</a>
```

But, if you use one form of quotation, you may use the other in your attribute values:

```html
<a href="https://www.example.com">Not so super simple rules.</a>
```
