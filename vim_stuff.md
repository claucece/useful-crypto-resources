## Some commands:

1. Select a column : `ctrl-V`
2. jump forwards to the start of a word: `w`
3. jump forwards to the start of a word (words can contain punctuation): `W`
4. jump forwards to the end of a word: `e`
5. jump forwards to the end of a word (words can contain punctuation): `E`
6. jump to the start of the line: `0`
7. jump to next paragraph (or function/block, when editing code): `}`
8. jump to previous paragraph (or function/block, when editing code): `{`
9. move back one full screen: `Ctrl + b`
10. move forward one full screen: `Ctrl + f`
11. move forward 1/2 a screen: `Ctrl + d`
12. move back 1/2 a screen: `Ctrl + u`
13. insert (append) after the cursor: `a`
14. join line below to the current one: `J`
15. change (replace) entire line: `cc`
16. change (replace) to the end of the word: `cw`
17. delete character and substitute text: `s`
18. redo:  `Ctrl + r`
19. comment all lines: `Ctrl + v, GI//` or `:%s/^/\///`
20. Go to first line: `gg`
21. Select till word appears: `v/foo`
22. Select current line and subsequent: `Shift+V n j`
23. Add in odd line: `:let i = 1 | g/^$/execute "normal i>item" . i | let i = i + 1`
24. Making a lits of numbers: `:put =range(11,15)`

## Interesting links:

* [Vim Cheat Sheet](https://vim.rtorr.com/)

## To see

* marks
