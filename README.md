# Neumorphism_Buttons

# Installation :

1. Copy the neumorph_buttons folder in your repo.
2. Add neumorphism as a dependency in your package.json file.

```json
{
  "dependencies": {
    "neumorphism": "file:../neumorph_buttons"
  }
}
```

# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    text-color: black;
}
```

# Button

<img src="sample_images/button.png" width="" height="">

Import:
```html
<element name='neubutton' src='../../../../../../node_modules/neumorphism/button/button.hml'></element>
```

Usage:
```html
<neubutton icon="common/icons/heart.png" width="250px" height="60px" border="50px" onclick="buttonClick">
  <text>Button</text>
</neubutton>
```

# Buttons

<img src="sample_images/buttons.png" width="" height="">

Import:
```html
<element name='neubuttons' src='../../../../../../node_modules/neumorphism/buttons/buttons.hml'></element>
```

Usage:
```html
<neubuttons  width="250px" height="60px" border="50px">
  <button slot="first">Left</button>
  <button slot="second">Right</button>
</neubuttons>
```
