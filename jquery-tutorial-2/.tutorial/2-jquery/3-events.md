# Events

In JS, you're probably used to using `addEventListener` to respond to clicks and other events, like this.

```js
const heading = document.querySelector('h1');
heading.addEventListener('click', function() {
  console.log('hello world');
});
```

In jQuery, you can just use `on`.

```js
$('h1').on('click', function() {
  console.log('hello world');
});
```

Try adding that inside your `<script>` element.
