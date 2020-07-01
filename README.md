xmodem-1k
=========

Georges Menie's Xmodem with minor modifications:

 * Support Xmodem(128 bytes) and Xmodem-1K/Ymodem(1024 bytes) transfers
 * Don't send a final (empty) packet on transfers that are
   exact multiples of the packet size, to make it work with some
   Xmodem receivers.
