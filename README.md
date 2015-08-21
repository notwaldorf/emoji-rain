# :sparkles: emoji-rain :sparkles:

`<emoji-rain>` is a Polymer element that makes it rain emoji on any page. Because it can.

<img width="500" alt="emoji rain" src="https://cloud.githubusercontent.com/assets/1369170/9401459/86c67a76-4784-11e5-8716-3300c96a7e20.gif">

☔️ The number of drops is configurable (by default it's set to 250). The `active`
attribute determines whether the emoji are raining, but you can also manually
`start()` and `stop()` the rain.

Example:
```html
  <emoji-rain drops="100" active></emoji-rain>
```

💸️ Optionally, you can also use the Twitter emoji instead of the native ones.
`twemoji.js` and all its images will only be loaded on demand, so if you don't
want to eat the performance cost, you don't have to:
```html
  <emoji-rain use-twemoji></emoji-rain>
```

# :sparkles::umbrella::joy_cat:
