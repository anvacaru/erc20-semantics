//NOTES: 
on transfer_0 the THROW is considered a revert
on transfer_1, no need for another balanceOf call because it is done automatically in transfer()
transfer_2 is redundant, because the logs are also emitted in transfer_1 and the logs can be seen in the log cell
how should I represent the `zero address`?
