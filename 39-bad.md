-- HUMAN RESOURCE MACHINE PROGRAM --

a:
    COPYFROM 14
    COPYTO   13
    INBOX   
b:
    SUB      15
    JUMPN    c
    COPYTO   12
    BUMPUP   13
    COPYFROM 12
    JUMPZ    d
    JUMP     b
c:
    ADD      15
d:
    OUTBOX  
    COPYFROM 13
    OUTBOX  
    JUMP     a


DEFINE LABEL 12
eJxTZWBguO7o7nrfbknkI9vv6Y9s/8x4YhOwHCjMUGfcXzHViae83iugsshftBYkJho1v+Va5OueqIg/
M65F5vaxJtxqOJAo2eCS8LitLHV63Yd00drMrOl1y7KfdyrmbpgA0nO+WKsnsNj6GIj9s/pkydqGg3lP
mu1zA7q7SoumLWk3nfq6x6vXbOqmuqrpnmWlUxhGwSgYBXQDAJ5fQDY;

DEFINE LABEL 13
eJzjZ2BgSMnx9kjJiQmZWmify1N6rry6+nFbaa1iW27DrYZFLe7FER2v4y52ubsClTJU1Nxq2F4ze/2X
WpazDKNgFIyCIQ8AxqoZpw;

