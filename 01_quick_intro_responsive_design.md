## The term "Responsive Design" coined
- Back to early 1990s when most monitors had screen dimensions of 640px x 480px, the web design was width-fixed. The "one-design-for-all" soon revealed issues when screens got bigger.
- Designers used percentage for column width which was known as liquid design. However, the issue had not been solved when the screens get so large or small.
- The need of designing for mobile devices was raising. At the beginning, companies had separate designs for each type of screen. It led to another problem of design and code management.
- Media queries were introduced. Combination of media queries and fixed-width layouts introduced adaptive design. Adaptive design allows to switch between fixed layouts at specific widths. Webs look good only on few screens. Web on devices with screen sizes falling in between, well, are not that good.
- Responsive design comes to get all screens covered. It is a mashup of media queries and liquid design. The term "responsive design" was coined by Ethan Marcotte in 2010. According to Marcotte, a responsive design must have three criteria: fluid grids, fluid media, and media queries.
## ```<meta>``` tag
- By default mobile phone browsers assume the original website width is 980px, which is wrong. So even if you used a liquid layout, the browser would apply a width of 980 pixels and then scale the rendered web page down to the actual width of the screen.
- Always include ```<meta name="viewport" content="width=device-width, initial-scale=1">```configuration. It tells the browser to assume the website width is the same as the device width and not to scale.
