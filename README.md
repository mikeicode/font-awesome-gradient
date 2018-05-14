## Add some flavor to you icons

You can use the [editor on GitHub](https://github.com/mikeicode/font-awesome-gradient/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Instead of adding a solid color to your [Font Awesome Icons](http://wpandsuch.com/tag/font-awesome/) with CSS why not add a custom gradient!

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
<i class="fa fa-facebook-square gradient-icon">
<i class="fa fa-linkedin-square gradient-icon">
<i class="fa fa-twitter-square gradient-icon">
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

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
ou can of course edit the color and direction of the gradient.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
