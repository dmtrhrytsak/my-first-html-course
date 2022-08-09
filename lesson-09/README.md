# Anatomy of an HTML document

Individual HTML elements are useless on their own. Now, let's study how different elements interact to produce a full HTML page:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Website of an HTML Developer</title>
  </head>
  <body>
    <p>Hello, page!</p>
  </body>
</html>
```

1. `<!DOCTYPE html>`: The document type. When HTML was first introduced (1991-1992), doctypes were intended to serve as links to a set of rules that the HTML page had to follow in order to be regarded proper HTML. Doctypes used to appear like this:

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

Now, the doctype has become a historical artifact that must be included in order for everything else to operate properly. The shortest string of characters that qualify as a valid doctype is `<!DOCTYPE html>`. This is all there is to it!

2. `<html></html>`: The `<html>` element. This element includes the whole page's content.
   It is also known as the root element.

3. `<head></head>`: The `<head>` element. This element serves as a container for what you wish to include on the HTML page **that isn't the content** that people will see. This contains keywords and a page description for search results, CSS to style content, character set declarations, and other elements.

4. `<meta charset="utf-8">`: The `<meta>` element. The charset attributes change your document's character set to UTF-8, which includes most characters from the great majority of human written languages. With this option enabled, the page can now handle any textual content that it may contain. There is no reason not to do so, and it may help you prevent some issues later. Examples of other meta-related elements are: `<link>`, `<style>`, `<script>`, `<title>`.

5. `<title></title>`: The `<title>` element. This defines the title of the page, which appears in the browser tab where the page is viewed.

6. `<body></body>`: The `<body>` element. This includes any text, photos, videos, playable audio tracks, or other material **that displays** on the page.

## Adding some features to an HTML document

Sharpen your skills by implementing the following tasks:

- Add the document's main title just below the beginning tag of the `<body>` element. This should be enclosed by a `<h1>` opening tag and a `</h1>` closing tag.
- Edit the `<p>` element content to to include information on a topic of interest to you.
- Wrap essential words with a `<strong>` starting tag and a `<strong>` ending tag to make them stand out in bold.
- Add a link tag `<a>`
