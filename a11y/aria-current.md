# Mark an element as in a relationship with the current page
The `aria-current` attribute can be used to indicate that an element is in a relationship with the current page.

```html
<ul>
<li><a href="/" class="home active" aria-current="page">Home</a></li>
<li><a href="/products" class="products">Products</a></li>
<li><a href="/contact" class="contact">Contact</a></li>
</ul>
```
This is better than using only css classes, since the aria attribute is recognized by screen readers.

More info: https://www.digitala11y.com/aria-current-state/

Source: https://twitter.com/a_sandrina_p/status/1258763691123707909
