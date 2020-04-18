# CSS

These are my notes learning w3school tutorial about CSS. <https://www.w3schools.com/css/>

## SYNTAX

```css
h1 {  
    color:blue;  
}
```

- h1 = selector
- {...} = declaration
- color = property
- blue = value

## SELECTORS

- Simple = tag name, id, class. I.e: p, #bibliography, .center, .large
- Combination = relationship between selectors I.e: p.center
- Pseudo-class = certain state. I.e: ¿¿??
- Pseudo-element = part of element. I.e: ¿¿??
- Attribute selector = attribute value. I.e: ¿¿??

Others:

- Universal selector: ```* {...}```
- Grouping selector: ```h1, h2, p {...}```

## ADD CSS

- External CSS: ```<link rel="stylesheet" type="text/css" href="mystyle.css">```
- Internal CSS: ```<style>...</style>```
- Inline CSS: ```style="..."```

Multiple styles, cascading order:

- Inline style (inside an HTML element)
- External and internal style sheets (in the head section)
- Browser default

## COLORS

- Name value: HTML 140 Colors <https://www.w3schools.com/colors/colors_names.asp>
- RGB values (red, green, blue): rgb(255, 99, 71)
- HEX values (hexadecimal): #ff6347
- HSL values (hue, saturation, and lightness): hsl(9, 100%, 64%)
- RGBA values (a=alpha): rgba(255, 99, 71, 0.5)
- HSLA values (a=alpha): hsla(9, 100%, 64%, 0.5)

## BACKGROUND

**Color:**

- background-color: red
- opacity: 0.3
- transparency using RBG -> rgba(xxx, 0.3)

**Image:**

- background-image: url()
- Repeat -> background-repeat: repeat-x;
- Position -> background-position: right top;
- Fix on position -> background-attachment: fixed;

**Shorthand:**

- background: #ffffff url("img_tree.png") no-repeat right top;

## BORDER

The CSS border properties allow you to specify the style, width, and color of an element's border.

## MARGINS

The CSS margin properties are used to create space around elements, outside of any defined borders.

- margin: auto; The element will then take up the specified width, and the remaining space will be split equally between the left and right margins.
