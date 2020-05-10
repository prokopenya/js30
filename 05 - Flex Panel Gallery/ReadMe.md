> This is a JavaScript practice with [JavaScript30](https://javascript30.com/) by [Wes Bos](https://github.com/wesbos) without any frameworks, no compilers, no boilerplate, and no libraries.

# 05 - Flex Panels Image Gallery

![](images/05_00.png)

CSS `flex`, `toggle()`, `includes()`, `transitionend`

### CSS flex

[CSS Flexible box layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)

### includes()

> Safari transitionend event.propertyName === flex */
>
> Chrome + FF transitionend event.propertyName === flex-grow */

due to there are different words between browsers, so we use `.includes()` to find the key word `'flex'` here, for matches them.

```
if (e.propertyName.includes('flex')) {
  this.classList.toggle('open-active');
}
```
