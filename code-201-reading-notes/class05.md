# Images

## Adding Images

`<img>` 

**To add an image into the page you need to use an `<img>` element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:**


- src

**This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site.**

- alt

**This provides a text description of the image which describes the image if you cannot see it.**

- title

**You can also use the title attribute with the <img> element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.**


`<img src="url" alt="Name" title="titleName" />`

***

## Height & Width of Images

- height

**This specifies the height of the image in pixels.**

- width

**This specifies the width of the image in pixels.**

**ُExample:**

`<img src="Url" alt="Name" width="600" height="450" />`

***

# Summary

* The <img> element is used to add images to a web page.
* You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
* You should save images at the size you will be using them on the web page and in the appropriate format.
* Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

***

# Color

## Foreground Color

- color

**The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:**

- rgb values

**These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)**

- hex codes

**These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80**

- color names

**There are 147 predefined color names that are recognized by browsers. For example: DarkCyan**

**Example:**

### color name

> `h1 {`
> `color: DarkCyan;}`

### hex code

> `h2 {`
> `color: #ee3e80;}`

### rgb value

> `p {`
> `color: rgb(100,100,90);}`


***

* Background Color

**"In css file"**

`body {`

`background-color: rgb(200,200,200);}`

`h1 {`

`background-color: DarkCyan;}`

`h2 {`

`background-color: #ee3e80;}`

`p {`

`background-color: white;}`

***

Summary

* Color not only brings your site to life, but also helps convey the mood and evokes reactions.
* There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
* Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.

***

# Text


* Specifying Typefaces

**font-family**

**The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.**

***


* Size of Type

**font-size**

**The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font.**

***

* Bold

**font-weight**

**The font-weight property allows you to create bold text.**

***

- Italic

**font-style**

**If you want to create italic text, you can use the font-style property.**

***

# Summary

* There are properties to control the choice of font, size, weight, style, and spacing.
* There is a limited choice of fonts that you can assume most people will have installed.
* If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
* You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.
* You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.