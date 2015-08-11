# fa-awesome

A simple web component to show font awesome icons. Quite limited in functionality, though. 
This element requires Polymer ^1.0.0 for it to work!

## How to use

Sorry I don't have a component page for it jet. But just have a look at the demo.html and the instructions below.

## Icon label

Set the label like so: `<fa-awesome>The Label Text</fa-awesome>`

## Attributes

`icon` = Name of the icon (without the 'fa-'). Defaults to 'flag'.
`size` = Set's the size of the icon. Use `lg`, `2x`, `3x`, `4x`, `5x`, `6x` or an empty string. Defaults to NO fa size class.
`label-left` = If true, the label is set on the left side of the icon.

Example: `<fa-awesome icon="flag" size="2x" label-left>The Flag</fa-awesome>`

## How to install

Clone this repository or use bower:

`bower install fa-awesome --save`