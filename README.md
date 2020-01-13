# gridFlexboxComparison

**This repository contains HTML/CSS files to demonstrate a direct comparison between Grid and Flexbox layout used in CSS**

Both the layouts display the same output but one file is completely based on Grid and the other is based on Flexbox.

This simple example demonstrates the file structure used in both the layouts to achieve a completely same result. However, Both the Layout modules should not be considered to be a replacement of the other, instead this example shows the purpose that is serverd by these layouts.

**In Grid layout follwing display attribute is used:**

```
.class{
    display: grid;
}
```

**In Flexbox layout follwing display attribute is used:**

```
.class{
    display: flex;
}
```

---

- To see the output of the file based on **Grid** [Click here](https://enunmuz.github.io/Grid-FlexboxComparison/grid.html)

- To see the output of the file based on **Flexbox** [Click here](https://enunmuz.github.io/Grid-FlexboxComparison/flex.html)

_Please note that both the outputs are visually identical, please look in [flex.css](./styles/flex.css) and [grid.css](./styles/grid.css) files to check for differences._

In Flexbox layout module we can see the extra `<div>`'s used to achieve the same output. However, in Grid layout module usage of `<divs>`'s is decreased which means:

- Less no. of Classes/Ids used.
- Less no. of `<div>`'s used.
- Faster Processing in larger pages.
- Less Complexity.
- Shorter Code.

Flexbox is best when used for one dimensional elements ( either for rows or columns ) whereas Grid layout is best when used for two dimensional elements at once ( for both rows and columns ) but when both these layouts are used together they fill the purpose easily.

**To see a demonstration of what a flexbox alone can do visit my other repo [Here](https://github.com/enunmuz/git_page_clone) where you can see the source code of the static webpage as well as the demo of the page which is based only on Flexbox.**
