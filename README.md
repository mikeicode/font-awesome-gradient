## Add some flavor to your icons

Instead of adding a solid color to your [Font Awesome Icons](https://fontawesome.com/v4.7.0/icons/) with CSS why not add a custom gradient!

[View demo site](https://mikeicode.github.io/font-awesome-gradient/) 

```markdown
<i class="fa fa-facebook-square gradient-icon">
<i class="fa fa-linkedin-square gradient-icon">
<i class="fa fa-twitter-square gradient-icon">
```

### The fun part

Target the CSS class above with this CSS:

```markdown
.gradient-icon {
    background: -webkit-gradient(linear, left top, left bottom, from(#ff5db1), to(#ef017c));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    display: initial;
}
```
You can of course edit the color and direction of the gradient.

![Image of Icons](http://wpandsuch.com/wp-content/uploads/gradient-icons-css.jpg)

