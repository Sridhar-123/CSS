# CSS
background-color: lightblue;  
color: white;  
text-align: center;  
font-family: verdana;  
font-size: 20px;

[Table of selector](https://www.w3schools.com/css/css_selectors.asp)
Colors: 
<h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
<h1 style="background-color:#ff6347;">#ff6347</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>

<p>Same as color name "Tomato", but 50% transparent:</p>
<h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>

hsl(hue, saturation, lightness)  
Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.
Lightness is also a percentage. 0% is black, 50% is neither light or dark, 100% is white

Saturation
Saturation can be described as the intensity of a color.

100% is pure color, no shades of gray.

50% is 50% gray, but you can still see the color.

0% is completely gray; you can no longer see the color.

Lightness
The lightness of a color can be described as how much light you want to give the color, where 0% means no light (black), 50% means 50% light (neither dark nor light) and 100% means full lightness (white).

Shades of Gray
Shades of gray are often defined by setting the hue and saturation to 0, and adjust the lightness from 0% to 100% to get darker/lighter shades:

HSLA Value
HSLA color values are an extension of HSL color values with an alpha channel - which specifies the opacity for a color.

An HSLA color value is specified with:

hsla(hue, saturation, lightness, alpha)


BACKGROUND 
>background-color
>background-image
>background-repeat
>background-attachment
>background-position
>background (shorthand property)

<!-- div {
  background-color: green;
  opacity: 0.3;
}
div {
  background: rgba(0, 128, 0, 0.3) /* Green background with 30% opacity */
} -->

