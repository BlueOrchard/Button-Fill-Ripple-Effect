## Button Fill Ripple

Make it so your button has a ripple effect that fills with the color of the ripple when a user hovers over it!

## Installation

Just include the CSS file in your project. After that, include the following class:

- btn-rpl

If you would like to add a default style to your button, add the following class as well:

- btn-init

If you want to change the color of the fill, select from the following:

- rpl-blue
- rpl-red
- rpl-green
- rpl-purple

Final Output Example:

```html
<button class="btn-init btn-rpl rpl-red">Test Button</button>
```

## Custom Colors

Want to make your own color? Add the following code to your styles:

```css
.rpl-custom:hover, .rpl-custom:hover:after{     /* Can be anything you want */
    color: #FFF;
    background: #a074d0;                        /* Custom color here */
    border-color: #a074d0;                      /* Make it the same as the above color */
}
```

Final Output Example:

```html
<button class="btn-init btn-rpl rpl-custom">Test Button</button>
```

## License

You are free to:

Share — copy and redistribute the material in any medium or format
Adapt — remix, transform, and build upon the material
for any purpose, even commercially.

Under the following terms:

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.