# Formula Describe Language #

only contains half-width character
> A-Z, a-z, ' " () + - * /

Variables are surrounded by a pair of apostrophes
> Variable X should be 'X'

Transcendental Functions can be represented by their name, and follows a pair of brackets. Here are supported funcions
> sin('x') &nbsp;cos('x') &nbsp;tan('x') &nbsp;arcsin('x') &nbsp; arccos('x') &nbsp; arctan('x')

>ln('x') &nbsp;lg('x')

These functions can be combines to a composite function
>sin(ln('x'))

Besides, normal Logarithmic Function should be represented in this way
>log('b','x')

And power function such as x^5 should be
>power('x',5)

Literal number
>5

>4+(9/3)

Other supported operators are listed as follow
> *+*&nbsp;-&nbsp;*&nbsp;/&nbsp;()&nbsp;

    * see order in https://en.wikipedia.org/wiki/Order_of_operations *
