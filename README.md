# SVG-ColorEditor
 A simple program to edit colors in an svg image using the HTML Color Picker element. 
 
 The entire process is made to run on only one thread, by using a Javascript *Promise* instance.
 
 The program first taken in an input svg Image.  
 
 The SVG-File is then parsed using a [DOMParser](https://developer.mozilla.org/en-US/docs/Web/API/DOMParser), and non empty fill attributes are collected from the *polygon* and *path* tags.  
 
 These values are then stored in actionable buttons. Clicking a button selects the color we want to replace in the SVG, and subsequent pick of a color from the *Color Picker* changes all instances of the selected color to the new color.
 
 A freely obtained svg from [svgstudio](https://svgstudio.com/pages/free-sample) was used for this program.
