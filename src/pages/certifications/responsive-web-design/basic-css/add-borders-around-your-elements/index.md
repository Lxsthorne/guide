---
title: Add Borders Around Your Elements
---
## Add Borders Around Your Elements

To add borders to the element, you must first create the class somewhere within the `<style>` tags:

```html
.thick-green-border {
  border-width: 10px;
  border-color: green;
  border-style: solid;
}
```
Or:

```html
 .thick-green-border {
    border: solid 10px green;
  }
```

Then, add the class attribute to the cat photo (Remember to leave a space):

```html
<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" 
     alt="A cute orange cat lying on its back.">
```

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
