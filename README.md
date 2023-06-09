
<h1 align="center"> FCC-3- CSS Color Marker </h1>

## Getting Started:
- It is a HTML project for exploring the deep basic understanding of HTML

## Tech stack:
- browser
- Code Editor (like Visual Studio Code/ notepad)

# FCC3-CssColorMarker
- webpages should start with a <strong>DOCTYPE html</strong> declaration.
- title element gives search engines extra information about the page.
    It also displays the content of that title element in two more ways:
    -   in the title bar when the page is open
    -   in the browser tab for the page when we hover on it.
- To tell browsers how to encode characters on the page, set the charset to utf-8. 
- utf-8 is a universal character set that includes almost every character from all human languages.
- meta elements are self-closing, and do not need a closing tag.
- multiple self-closing meta elements on a web page is acceptable.
- To design a page that looks the same on all devices we use these attributesin meta tag (name="viewport" content="width=device-width, initial-scale=1.0")
- to link styles file add a <strong>link</strong> tag with href attribute set to styles.css
- To center your marker on the page, set its margin property to auto. This sets margin-top, margin-right, margin-bottom, and margin-left all to auto.
- When the <strong>shorthand margin property</strong> has two values, it sets margin-top and margin-bottom to the first value, and margin-left and margin-right to the second value. (ex: margin:10px auto)
- <strong>Multiple classes</strong> can be added to an element by listing them in the class attribute with space. If you add multiple classes to an HTML element, the styles of the first classes you list may be overridden by later classes.
- two main color models: 
    - the additive RGB (red, green, blue) model used in electronic devices, 
    - the subtractive CMYK (cyan, magenta, yellow, black) model used in print.
-  In RGB model, colors begin as black, and change as different levels of red, green, and blue are introduced. we can see this with the CSS rgb function. (ex: background-color: rgb(0, 0, 0))
- RGB function : A function is a piece of code that can take an input and perform a specific action. The CSS rgb function accepts values, or arguments, for red, green, and blue, and produces a color:
 - rgb(red, green, blue);
 - Each red, green, and blue value is a number from 0 to 255. 0 means black and 0% of that color, 255 means 100% of the color.
- Shorthand padding (ex: padding:10px 0)
- rgb(255, 255, 255) gives white color. Secondary colors are the colors you get when you combine primary colors
- <strong>Tertiary colors</strong> are created by combining a primary with a nearby secondary color.
- to apply color to an element with CSS is with hexadecimal or hex values.
    - Hex color values start with a # character and take six characters from 0-9 and A-F.
    - decimal (or base 10 values) go from 0 - 9. Hexadecimal (or base 16 values) go from 0 - 9, then A - F. 
    - With hex colors, 00 is 0% of that color, and FF is 100%. to Lower the intensity of green we may use #00FF00 to #007F00
- The HSL color model, or hue, saturation, and lightness, is another way to represent colors.
    - The CSS hsl function accepts 3 values: 
        - number from 0 to 360 for hue.
        - a percentage from 0 to 100 for saturation.
        - a percentage from 0 to 100 for lightness.
    - Saturation is the intensity of a color from 0%, or gray, to 100% for pure color.
    - Lightness is how bright a color appears, from 0%, or complete black, to 100%, complete white, with 50% being neutral.
- There is another way to set flat colors in CSS
    - we may use a color transition, or gradient, on an element.
    - A gradient is when one color transitions into another.
    - The CSS linear-gradient function lets you control the direction of the transition along a line, and which colors are used.
    - linear-gradient(gradientDirection, color1, color2, ...);
    - gradientDirection is the direction of the line used for the transition. color1 and color2 are color arguments
    - color can be anything including color keywords, hex, rgb, or hsl.
    - ex: background: linear-gradient(90deg, rgb(255, 0, 0) 75%, rgb(0, 255, 0), rgb(0, 0, 255));
    - If no gradientDirection argument is provided to the linear-gradient function, it arranges colors from top to bottom, or along a 180 degree line, by default.
- With the CSS <strong>opacity</strong> property, you can control how opaque or transparent an element is.
    - 0 or 100% - completely transparent
    - 1.0 or 100% - completely opaque like it is by default.
- The <strong>alpha channel</strong> controls how transparent or opaque a color is, similar to the opacity property.
- The <strong>rgba function</strong> works just like the rgb function, but takes one more number from 0 to 1.0 for the alpha channel:
    - rgba(redValue, greenValue, blueValue, alphaValue);
    - we can also use hsl and hex colors in alpha channel. 
    - background-color: rgba(255,255,255,50%);
-  default display property for div elements is block. To position two div elements on the same line,we will set their display properties to inline-block.
- The border-left shorthand property:
    - border-left: width style color;
    - ex: border-left: 10px solid black;
- The box-shadow property lets you apply one or more shadows around an element.
    - box-shadow: offsetX offsetY blurRadius spreadRadius color;
    - This is how the offsetX and offsetY values work:
        
        - both offsetX and offsetY accept number values in px and other CSS units.
        - a positive offsetX value moves the shadow right and a negative value moves it left
        - a positive offsetY value moves the shadow down and a negative value moves it up
        - if you want a value of zero (0) for any or both offsetX and offsetY, you don't need to add a unit. Every browser understands that zero means no change.
        - spreadRadius - 
        - with the box-shadow property you can finalize the shadows:
            - box-shadow: 0 0 20px 0 red

## Deploy on Vercel:
- vercel Link -https://fcc-3-css-color-marker.vercel.app/

## Built by

👤 **Sangeetha Ramkumar**

- [LinkedIn](https://www.linkedin.com/in/sangeetharamkumar)
- [GitHub](https://github.com/Sangi19)
- [E-mail](sangiammu1020@gmail.com)




