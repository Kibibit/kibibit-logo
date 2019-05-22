# kibibit-logo

logo css to add to projects.

## Setup
add the css file as a dependency
```html
<link rel="stylesheet" href="kibibit.io/kibibit-logo/kb-logo.css">
```

## How to use

Basic HTML structure:

```html
<div id="logo" class="kb-logo full-logo"><span class="letter">k</span>

  <div class="shape-animation shape-one to-red">
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
  </div>

  <div class="shape-animation shape-zero">
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
  </div>

  <div class="shape-animation shape-one to-blue middle">
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
  </div>

  <div class="shape-animation shape-zero">
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
  </div>

  <div class="shape-animation shape-one to-yellow">
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
  </div>
  <span class="letter">t</span>

  <div class="k1b1b0t-mouth-container">
    <div class="k1b1b0t-mouth">[<span class="mo-an">||||</span>]</div>
  </div>
</div>
```
The inner HTML inside the `kb-logo` should work as is. you can create a
component to add this html snippet (for example: `<kb-logo></kb-logo>`)

### Modifier classes
**NORMAL STATE:** logo is displayed as **10101**
- `always-k-t` - always show k & t letters (even in loader and 10101)
- `always-squiggly` - add drawn animation to the logo (needs an additional **svg definition**)
- `squiggly` - make only the loader squiggly (needs an additional **svg definition**)
- `purple` - make basic text purple (you can simply change the white text to any color with the `color` css attribute on `kb-logo`)
- `no-extra-colors` - remove the colors of the 3 i's. only show the basic text colors
- `loader` - change logo to loader animation
- `full-logo` - show the actual named logo of `kibibit`
- `k1b1b0t` - transform the logo into k1b1b0t
