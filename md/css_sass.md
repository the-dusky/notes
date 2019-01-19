SASS Notes
==========

& - Ampersand
---

* The ampersand copies the name of the parent selector.

Example:

This:

```css
.parent {
    position: relative;
    &--child {
        position: absolute;
    }
}
```

is identical to:

```css
.parent {
    position: relative;
}
.parent--child {
    position: absolute;
}
```