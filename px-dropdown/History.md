v0.3.0
==================
* make it more obvious it is possible to scroll by reducing the height of the dropdown by half an item's height if the dropdown has scrollbars
* added bound-target attribute: if set the dropdown will always try to fit within this HTMLElement
* fixed setDivWidth on click function bug.

v0.2.0
==================
* changed the way the initial text is passed in (added attribute display-value)
* added a hide-chevron attribute
* Updated styles
* max container character count now also applies to the px-text portion of the component.

v0.1.0
==================
* added smart orientation which detects if the dropdown will show below the viewport, and display the dropdown above the element clicked.
* Updated styles/spacing/chevron
* removed the need to call px-dropdown-chevron - it's baked into the component now.

v0.0.3
==================
* Updated License

v0.0.2
==================
* added hover and opened styles/classes

v0.0.1
==================
* Initial release, px-dropdown supports receiving an array of items, and displays a dropdown list when either the text or the chevron are clicked. A click on the item itself fires off a "px-dropdown-click" event, and passed the click event with it.
