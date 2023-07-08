To link a JavaScript file in an HTML file, you use the `<script>` tag with the `src` attribute. The `src` attribute specifies the path to the JavaScript file. Here's an example:

```html
<!DOCTYPE html>
<html>
<body>

<h1>Hello, World!</h1>

<script src="script.js"></script>

</body>
</html>
```

In the example above, the JavaScript file named "script.js" is linked to the HTML file.

This file should be located in the same directory as the HTML file. If it's located in a different directory, you'll need to modify the path in the `src` attribute accordingly.

For instance, if the JavaScript file is in a subdirectory named "js", the `src` would be "js/script.js". If the JavaScript file is in a parent directory, the `src` would be "../script.js".

It's important to note that the browser will block rendering of the HTML until it has finished downloading and processing the JavaScript file. To avoid potentially long blocking times, especially for larger scripts, it's often recommended to place the `<script>` tag right before the closing `</body>` tag.

If you want to make sure that your script doesn't block rendering of the HTML, you can also add the `async` or `defer` attribute to the `<script>` tag. Both of these attributes change when and how the script is executed:

- `async`: The script is executed asynchronously with the rest of the page. The script is executed as soon as it's ready, even if the rest of the page has not finished rendering. This can speed up page load times, but you can't guarantee that scripts will load in any specific order.
  
- `defer`: The script execution is deferred until the page has finished parsing. This is useful when the script needs to be executed after the complete page is parsed and ensures scripts are executed in the order they were specified in the HTML. 

Here's how to use these attributes:

```html
<script src="script.js" async></script>
<!-- or -->
<script src="script.js" defer></script>
```

Keep in mind, `async` and `defer` are only effective when the script is added in the `<head>` section of the HTML document. If the script is placed right before the `</body>` tag, the effect of `async` and `defer` will be negligible as the page would have mostly finished parsing by then.