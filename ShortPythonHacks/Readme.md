Short Python Hacks
===

Find shortest string
> `min([s0, s1, s2], key=len)`

Find replacing segment in a string `abcabc => abc * 2`
> `i = (s + s).find(s, 1)`

Get columns of mattrix represented as a list of lists
> `for col in zip(*A): print(col)`

Append a list of characters to the end of a list of strings:
> `zip([['abc','efg'], ['d', 'h']])`
            
Get alphabetics from a list of words:
> `chars = set(''.join(words))`

Transpose a matrix:
> `z = list(map(list, zip(*A)))`
