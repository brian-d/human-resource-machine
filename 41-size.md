-- HUMAN RESOURCE MACHINE PROGRAM --

a:
    COPYFROM 24
    COPYTO   0
    COPYTO   20
b:
    INBOX   
    JUMPZ    h
    COPYTO   23
c:
    COPYFROM [20]
    JUMPZ    f
    COPYFROM 23
    SUB      [20]
    JUMPN    d
    BUMPUP   20
    JUMP     c
    COMMENT  0
d:
e:
    COPYFROM [20]
f:
    COPYTO   22
    COPYFROM 20
    COPYTO   21
    BUMPUP   20
    COPYFROM 23
    COPYTO   [21]
    COPYFROM 22
    JUMPZ    g
    COPYTO   23
    JUMP     e
g:
    COPYTO   [20]
    COPYTO   20
    JUMP     b
    COMMENT  1
h:
    COPYFROM 24
    COPYTO   20
i:
    COPYFROM [20]
    JUMPZ    a
    OUTBOX  
    BUMPUP   20
    JUMP     i


DEFINE COMMENT 0
eJwzY2BgeKCWm/BALaBSSW1NL5DLIK9ubQOis60yY4vNJRuKzSdXr7L6kzXf7n2ipOOfrEnOAZUBLqkd
IDX+MWviL0SviIkJfx79LHhnRnowQ97y4P6KvpgVXX0xP6beC3OeB1JXmC7bPDcvpmly0fS688UhNd6l
HCVnS+pyIgu+p2tlBVR+SJ/fkpfxvl8r68fU+7nO8yILWOaD9Kk1d5XqNRROTG7hKZfoYCn06m3KP9LP
UbJn0vQ6kPzh5Qcd6lY2zQWxpy1gyKte9Sfr0k7rLIZRMApGAVEAAF+SVbk;

DEFINE COMMENT 1
eJwzY2BgkNKcHhCjUZezTOXgnGUqXYuBQgyLVb9b8uvqGdcZrzEsNtczTrats7vpcNZzlsOjiLn2Zunz
7fZmr7V0L95h6l3GbnCunEfvZAlIn6mfYpup35renz4Mc2y9A5aX+xZONAhIaE0NOVd+I8I+91pkXU5Q
9NFCkNrE3LqctOymuSD21MJriiB6UQtHyZPm2Y1PmvuXPWn+PEmhdUn7zfbpdf3dglVNExjm1EyavR6k
zmeJkdnpJZOrzy4unTJ5oehqkJjRtKpM92V1OZN21uUwjIJRMAqIAgAKSlP7;

DEFINE LABEL 20
eJxjZ2BgaEzcknogsa2oJUGrxyXh8RagEENdUqY+wygYBaNg2AMASt0JaQ;

DEFINE LABEL 21
eJwTZGBgOGoQUnPU4P1eIJOhwUgtGkQbBLzvfx1oNMkl4c+MRzlNcz3LnOeBxJNbBH2WN02uXt60YYJa
M+/SRS2p2xjQQGbW47a7ebLNVwuv1QoW91ecL24rEiyuyrxeUJq2INe54G2GWmdh+s5pheks83UyA5bL
54WsAuljnuBc4NtzMG9Kp3NBVDtHSUJrQOXzpvktqxpz+7Ibq6a/bGSZ/7Bl8srpHbfW+fbMXu/VK7kO
pC9yfkT9slmCKx7PPjjnxny1Tq6lk6sPL++vQHfXKBgFowATAABrd1je;

DEFINE LABEL 22
eJxTZmBgCNP6nq6ktmHCMhXepekqG/Y9VTE/DBRmKFTYMrnZ8PMkEHuDxY+pBRZGBzStr62OcPw8Scyp
anqok/eSVo+6WaV+pVOK/M2m5gZOXglSa5S+pndb6oodu5NFb4L421JnN67LuFZ7vGx6nWVNTNOmusdt
6+szuwvqzabyl0ium1w0e/2KrNnrGUbBKBgFdAcAGFo6kw;

DEFINE LABEL 23
eJzzZWBg+GImG1phOj3A0WiyL7/uJZ9ENVH/DwpLIitl/2T9lplet1N2RVeJ/M5pbxVZ5j9WPbfUT3f6
GhbDiLV2xgHLgdoZntgoti2y3TBB2qFp7iRn3qXebueWtrvzLt3vxTDHwlevf4ufbDNI3cToJe0To/uX
XYium+Uer9jmkiDb/ClNsAokN7lodmNYofeSqYUH53iXJrQeqphcbVnTXwGSW9Sypjei431/04T3/eVT
1vTmT5/fsm76rYYP0wIqqyafLOHubSu613qpammzZINm05L27Eb72anNoqtntT/ffqT/9S6QGXfnLmm/
Ozdibcw83qVXFxhN8l+s2Ma1NKbJfVlME9OKx23Vqz5PKlvTtuDrmmurQervbznqfGXH5OrzuzgWgfgr
NrYVKW5pyv941CydYRSMgmEEAG8xiWc;

DEFINE LABEL 24
eJyTY2Bg+Fi3w6q1fIfV3Txnp8wsb4/Nadf8O+M+p/jHtBUFRUs2TIyums4Vd26pe3zIqsqUexufZj/f
Llj8etfeqte7FrVIrpvecW7pxa6muWd6cvtO9s5u7OplyOPrMUqR6JgdrN141BloBQNfz0GH7tK92Z/S
Pk+6EH1tNcMoGAWjYFAAALWVOeU;

