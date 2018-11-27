# Cheat Sheet about Vim

## Movement

`h`	left
`l`	right
`k`	up
`j`	down


`H`	jump to TOP of sreen 
`M`     Jump to MIDDLE of screen
`L`     Jump to BOTTOM of screen
`C-b`   Move back one full screen (page up)
`C-f`   Move forward one full screen (page down)
`C-d`   Move forward 1/2 screen; half page down
`C-u`   Move back (up) 1/2 screen; half page up

`w`        jump by start of words (punctuation considered words)
`e`        jump to end of words (punctuation considered words)
`b`        jump backward by words (punctuation considered words)
`0` (zero) start of line
`^`        first non-blank character of line
`$`        end of line
`G`        bottom of file
`g`        top of file

"good to know"

`E`        jump to end of words (no punctuation)
`W`        jump by words (spaces separate words)
`B`        jump backward by words (no punctuation)
`G`        goto line #
`gg`       goto line #


editing

`x         Delete char UNDER cursor
`X`        Delete char BEFORE cursor
`x`        Delete the next # chars. starting from char under cursor
`dw`       Delete next word
`dW`       Delete UP TO the next word
`d^`       Delete up unto the beginning of the line
`d$`       Delete until end of the line 
`D`        See d$, delete until end of the line  
`dd`       delete whole line
`dib`      Delete contents in parenthesis '(' ')' block (e.g. function args)
`diB`      Delete inner '{' '}' block
`daB`      Delete a '{' '}' block
`das`      Delete a senctence
`diw`      Delete word under cursor
`df<c>`    Delete until next occurence of <c> (char) found (including <c>) [in single line]
 dt<c>`    Delete until next occurence of <c> (char) found (without <c>!!!) [in single line]











##
