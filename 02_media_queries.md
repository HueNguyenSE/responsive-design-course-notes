## Syntax
```
@media type and (feature) {
  ...
}
```
**Types (or outputs) could be:**
- ```screen``` used for computer screens, mobile phone screens, tablet screen..., 
- ```print``` used for printers
- ```speech``` used for screen reader (read-out-loud feature)
- If a feature is not specified, by default it will apply to all media type devices

**Features are varied. Some popular features are:**
- width and height of devices
- width and height of viewport
- orientation
- resolution
## Extended syntax
```
@media not|only type and (feature) {
  ...
}
```
## Example
In the stylesheet, you add a media query to specify styles for print in landscape orientation
```
@media print and (orientation: landscape) {
    body {
    background-color: white;
    color: black;
  }
}
```
You could have a separate stylesheet for print and landscape orientation. Then you need to link to that file.
```
<link rel="stylesheet" href="landscape.css" @media="print and (orientation: landscape)">
```
## Good practices
- Adjust styles based on viewport size
- Choose breakpoint based on the content rather than popular device sizes
- Use length unit based on the type of content
  - Use ```px``` if the content is mostly image-based
  - Use relative unit such as ```em``` if the content is mostly text
