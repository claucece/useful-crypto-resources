----------------------------------------------------------------------------
# Programming

## General

### ExpMod
* [David Neto's code page](http://www.cs.utoronto.ca/~neto/code/fastexp.scm): Scheme and Ideal Turing
* [Bitwise operators (Python)](https://wiki.python.org/moin/BitwiseOperators)

### Floating point
* [Gustavo's IEEE-754 Brain Teaser](https://www.goinggo.net/2013/08/gustavos-ieee-754-brain-teaser.html) by William Kennedy
* [IEEE Standard 754 Floating Point Numbers](http://steve.hollasch.net/cgindex/coding/ieeefloat.html) by Steve Hollasch 
* [Comparing Floating Point Numbers, 2012 Edition](https://randomascii.wordpress.com/2012/02/25/comparing-floating-point-numbers-2012-edition/) by randomASCII
* [Example: Converting to Float](http://class.ece.iastate.edu/arun/CprE281_F05/ieee754/ie5.html)

## Padding
* [Structure Member Alignment, Padding and Data Packing](http://www.geeksforgeeks.org/structure-member-alignment-padding-and-data-packing/) 

## Golang

### General
* [The Go Blog](https://blog.golang.org/)
* [Open My Mind](http://openmymind.net/) by Karl Seguin.
* [Go Playground](https://play.golang.org/)
* [Useful resources](https://github.com/golang/go/wiki#getting-started-with-go)

### Naming
* [What's in a name?](https://talks.golang.org/2014/names.slide#1) by Andrew Gerrand
* [Name](https://golang.org/doc/effective_go.html#names) by Effective Go
* [Package names](https://blog.golang.org/package-names)
* [Some questions](http://stackoverflow.com/questions/38616687/which-way-to-name-a-function-in-go-camelcase-or-semi-camelcase) 

### Books
* [An Introduction to Go Programming](https://www.golang-book.com/books/intro)

### Strings
* [Access to the unicode and convert to string](http://stackoverflow.com/questions/19231506/go-golang-access-string-as-character-value)
* [Count](https://golang.org/src/strings/strings.go?s=1960:1989#L67)

### Types
* [Understanding Type in Go](https://www.goinggo.net/2013/07/understanding-type-in-go.html)

### Convert
* [Rune to Int](http://stackoverflow.com/questions/21322173/convert-rune-to-int)
* [strconv](https://golang.org/pkg/strconv/)
* [Don't abuse math.Max / math.Min](http://mrekucci.blogspot.com/2015/07/dont-abuse-mathmax-mathmin.html)

### Arrays and slices
* [Controlling Array Growth in Golang](http://openmymind.net/Controlling-Array-Growth-In-Golang/) by Karl Seguin
* [Arrays, Slices and Maps](https://www.golang-book.com/books/intro/6)
* [Arrays, slices (and strings): The mechanics of 'append'](https://blog.golang.org/slices)
* [Go Slices: usage and internals](https://blog.golang.org/go-slices-usage-and-internals)
* [SliceTricks](https://github.com/golang/go/wiki/SliceTricks)
* [Multi-dimesional arrays](https://www.tutorialspoint.com/go/go_multi_dimensional_arrays.htm)

### ForLoop
* [Control structures - Go for loop, break, continue, range](http://golangtutorials.blogspot.com/2011/06/control-structures-go-for-loop-break.html)

### Go Check
* [GoCheck](https://github.com/go-check/check)
* [Language Specification](https://golang.org/ref/spec#Conversions)

### Type Assertions
* [Language Specification](https://golang.org/ref/spec#Type_assertions)

### Conversions
* [A Guide to Types and Casting in Golang](http://blog.stoneriverelearning.com/a-guide-to-types-and-casting-in-golang/) by Gerard Millares
* [GoLang interface{} - 2 type conversions, type assertions, type switches](http://golang-basic.blogspot.com/2014/06/golang-interface-2-type-conversions.html) by Swati Soni

### Constants
* [iota: Elegant Constants in Golang](https://splice.com/blog/iota-elegant-constants-golang/) 
* [constants](https://blog.golang.org/constants)

### Errors
* [Illegal octal digit error](http://www.perlmonks.org/?node_id=768999)


### Talks
* [General](https://talks.golang.org/)
* [5 things I love (or why you should learn Go)](https://www.youtube.com/watch?v=fsTOOPB1TBY) by Andrew Gerrand
* [How go was made (or why you should learn Go)](https://www.youtube.com/watch?v=0ht89TxZZnk) by Andrew Gerrand
* [Closing day keynote](https://www.youtube.com/watch?v=dKGmK_Z1Zl0) by Andrew Gerrand


----------------------------------------------------------------------------

# Design

## Css
* [You don't need javascript](https://github.com/you-dont-need/You-Dont-Need-Javascript)

## Vim
* [Xterm256 color names for console Vim](http://vim.wikia.com/wiki/Xterm256_color_names_for_console_Vim)
 
----------------------------------------------------------------------------
# Useful
* [ADR tools](https://github.com/npryce/adr-tools)
* Topological math: [Topological phase transitions and topological phases of matter](https://www.nobelprize.org/nobel_prizes/physics/laureates/2016/advanced-physicsprize2016.pdf)

----------------------------------------------------------------------------
# Code for Tor Browser High Security Mode
In high security mode, Tor only allows PNG images to be available.

If your website must support non-PNG images like SVG, you can set up a fallback image
like so [(Ref.)](https://css-tricks.com/a-complete-guide-to-svg-fallbacks/):

1. With HTML:
```
<object data="your.svg" type="image/svg+xml"> <img src="yourfallback.jpg" /> </object>
```
2. With CSS, which naturally throws away rules that the browser doesn't understand:
```
.image-with-fallback {
    background-image: url(fallback.png);
        background-image: url(your.svg), none;
}{}
```
[Why is SVG a problem? Pg 16 in this iSEC report](https://github.com/iSECPartners/publications/blob/052caf9c9c683ec0bed55782714df4d35c38f107/reports/Tor%20Browser%20Bundle/Tor%20Browser%20Bundle%20-%20iSEC%20Deliverable%201.3.pdf).
