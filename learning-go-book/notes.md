# Learning Go
## An Idiomatic Approach to Real-world Go Programming

Page 5
Go package download locations

Page 6
Go defines an standard way of formatting

Page 7
Semi colon insertion rule

Go Wiki: Go Code Review Comments
https://go.dev/wiki/CodeReviewComments

golint and go vet

go playground
play.golang.com

Page 33
Go uses Camel Case

Arrays and Slices

Page 36
GO has only one dimensional Arrays

Page 38
nil is set in place of no value, it's slightly different from null

slices cannot be compared to other slices, it can only be compared with nil

Page 49
Slicing a multibyte sized characters (like emojis)
rune to string conversion
int to string conversion (demo)

Page 6
Go defines an standard way of formatting

Page 7
Semi colon insertion rule

Go Wiki: Go Code Review Comments
https://go.dev/wiki/CodeReviewComments

golint and go vet

go playground
play.golang.com

Page 33
Go uses Camel Case

Arrays and Slices

Page 36
GO has only one dimensional Arrays

Page 38
nil is set in place of no value, it's slightly different from null

slices cannot be compared to other slices, it can only be compared with nil

Page 51
Instead of using slice and index in strings, use extract substring and code pints from strings using functions in strings and unicode utf8 package.

Page 52
When to use Maps/Slices
use maps when the order of elements doesn't matter. Use slice when the order of element is important.

GopherCon 2016: Inside the Map Implementation - Keith Randall
https://youtu.be/Tl7mi9QmLns

Page 54
When accessing an element in map, if the key doesn't exist it doesn't return error.

Page 56
Go doesn't have classes because it doesn't have inheritance. structs can be used similar

Page 60
can convert a struct and anonymouns struct without type conversion.
