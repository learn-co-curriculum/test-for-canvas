# Test for Canvas

## Intro

This content is for testing and addressing bugs in github-to-canvas


## Spacing Issues


### Headers with no space

cause problems

### Headers with no space
cause problems

```js
code snippets need spacing
```

```js
code snippets need spacing
```
here

and here
```js
code snippets need spacing
```



1. lists run together

2. without new lines 

3. between every item

1. lists run together
2. without new lines
3. between every item

In line code snippets like `<h1>this</h1>` or `Record > CD` shouldn't be affected by `--contatins-html` option

Neither should <, >, <>

<h1>Header should render</h1>

```html
<h1>Header shouldn't render</h1>
```

```
<h1>Header shouldn't render</h1>
```


<!-- # More than one top-level header causes problems -->
