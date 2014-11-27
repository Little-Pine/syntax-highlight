# [`<syntax-highlight>`](http://1000ch.github.io/syntax-highlight)

## About

Code syntax highlight element.

## Usage

Import `syntax-highlight.html`.

```html
<link rel='import' href='syntax-highlight.html'>
```

Put `<syntax-highlight>` tag including code.

```html
<syntax-highlight><script>
  var foo = 'Hello!';
</script>
</syntax-highlight>
```

`<syntax-highlight>` behave such like `<pre>`.

## Attributes

### `lang=<String>`

Specify the code language.

http://highlightjs.readthedocs.org/en/latest/css-classes-reference.html

### `theme=<String>`

Select highlight theme. 

https://highlightjs.org/static/demo/

## License

MIT
