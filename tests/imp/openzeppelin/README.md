totalSupply:
erc20k:
real    0m8.974s
user    0m13.938s
sys     0m2.844s
java:
real    1m23.654s
user    1m48.406s
sys     0m17.125s 
ocaml:
real    0m30.421s
user    0m29.625s
sys     0m14.281s

balanceof0
erc20k:
real    0m9.029s
user    0m14.016s
sys     0m2.734s
java:
ocaml:
balanceOf1
erc20k
real    0m8.803s
user    0m13.625s
sys     0m2.813s
java:
ocaml:

transfer_0
real    0m9.327s
user    0m15.422s
sys     0m2.734s



//NOTES: 
on transfer_0 the THROW is considered a revert
on transfer_1, no need for another balanceOf call because it is done automatically in transfer()
transfer_2 is redundant, because the logs are also emitted in transfer_1 and the logs can be seen in the log cell
how should I represent the `zero address`?