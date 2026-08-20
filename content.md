To include a hyperlink in an HTML document, you use the `<a>`{.html} tag. For example:

```html
<a href="https://www.imperial.ac.uk">Imperial College London</a>
```

This will render as "<a href="https://www.imperial.ac.uk">Imperial College London</a>". The text within the tags is the link text that will be displayed to the user. The `href`{.html} attribute specifies the URL of the page the link goes to.

# Relative Links

In the example above, we used an absolute URL (starting with `https://`). You can also use a relative URL, which is relative to the current page. For example:

```html
<a href="../../accounts/goals">My Goals</a>
```

This will render as "<a href="../../accounts/goals">My Goals</a>". In the example above, the `..` sections represent going up one level in the url of the website. In many ways this is similar to a relative path to a local file.
