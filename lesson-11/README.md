# Special characters in HTML

The characters `<`, `>`, `"`, `'` and `&` are special characters in HTML. They are aspects of the HTML syntax. So, how can you include one of these unique characters into your code? For example, if you don't want an ampersand `&` or less-than symbol `<` to be treated as code.

This is done through character references. These are unique codes that represent characters and are only to be used in these specific circumstances. Each character reference begins with an ampersand (`&`) and ends with a semicolon (`;`).

| Literal character | Character reference equivalent |
| ----------------- | ------------------------------ |
| <                 | `&lt;`                         |
| >                 | `&gt;`                         |
| "                 | `&quot;`                       |
| '                 | `&apos;`                       |
| &                 | `&amp;`                        |

There are two paragraphs in the example below:

```html
<p>In HTML, you say that you a cool HTML developer using the <p>element.</p>

<p>In HTML, you say that you a cool HTML developer using the &lt;p&gt; element.</p>
```

The first paragraph is incorrect, as shown below. The browser reads the second occurrence of `<p>` as the beginning of a new paragraph. The second paragraph looks good since it uses angle brackets to refer to characters. 

```
In HTML, you say that you a cool HTML developer using the
element.

In HTML, you say that you a cool HTML developer using the <p> element.
```

> ℹ️ Note that you do not need to utilize entity references for any other symbols because current browsers will handle the real symbols perfectly fine if your HTML's character encoding is set to UTF-8. 
