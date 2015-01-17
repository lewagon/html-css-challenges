## Background & Objectives

Use advanced selectors (id, class, grouping, descendant selectors) to fine-tune your page with a more subtle design.

## Specs

Here is [your objective](http://lewagon.github.io/html-css-challenges/04-advanced-selectors/). Any time you want to name an element of your page, ask yourself:

- Should I use a `class` or an `id`?
- What name should I pick for my class?

Try to use **generic class names** as much as you can. Think **modularity** & **re-usability**. Try to step back from the page you're coding when choosing class names. Consider each CSS class as nice re-usable design that is not only linked to your current page but that will be re-used everywhere on your website. Getting this mindset is often the main difficulty for CSS beginners.

## Tips & Resources

To design your lists of icons, you should change the `block` behavior of list items by inlining them. The problem with 100% `inline` elements is that their width automatically fits their content so that you cannot change it. To keep control on list item width, make them `inline-block` elements. Such elements cumulate inline behavior but and box model properties (like `width`), yeah! Here are the corresponding CSS rules.

```css
ul > li{
  display: inline-block;
  width: 90px;
}
```