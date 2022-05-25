# assessment

## Import
`\usepackage[nohead]{assessment}`

`nohead` option removes headers on all pages beyond the first.

## Commands
`\important{keyword}{text}`

Inserts a paragraph with `keyword` in small caps, followed by a colon, space, and then the text.

`\question{text}`

Inserts the current question number, a period, space, and then the text.

`\questiond[lines]{file}{width}{text}`

Inserts an image on the right side of the page and wraps text around. `width` is the scale factor of the text width for the image, and `lines` is the number of lines of text to wrap. Inserts the current question number, a period, space, and then the text.

`\option[vspace]{text}`

Used for multipart questions or multiple choice answers. `vspace` is the amount of space to insert above the option. Inserts the option number (alphabetical), a period, space, and then the text.
