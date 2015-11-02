-- HUMAN RESOURCE MACHINE PROGRAM --

    INBOX   
a:
b:
    COPYTO   0
    INBOX   
    SUB      0
    JUMPZ    c
    INBOX   
    JUMP     a
c:
    ADD      0
    OUTBOX  
    INBOX   
    JUMP     b


