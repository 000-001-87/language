# PointerL
## Description
PointerL is a programming language that uses a bitwise pointer to move over sets of bytes and flip their bits to make characters like letters. It has bitwise operations, allows for I/O and loops, so it could theoretically be Turing complete.
## Commands
```  
> - move pointer right
< - move pointer left
+ - bit of pointer on
- - bit of pointer off
. - output into address(default: display)
* - finish byte
= - copy byte
; - pointer to byte or bit mode
@ - and operator
% - not operator
$ - sum of 2 bytes
& - output into register
: - input from address
{} - loop brackets
```
## Examples
### Hello World
```
>>>>+ >>>>>>+ * .        ; H (72 = 01001000)
>>>>+ >>>>+ >>>+ >>>>>>+ * .        ; e (101 = 01100101)
>>>>+ >>>>+ >>>>>>+ * .             ; l (108 = 01101100)
>>>>+ >>>>+ >>>>>>+ * .             ; l (108 = 01101100)
>>>>+ >>>>+ >>>+ >>>>>>+ * .        ; o (111 = 01101111)
>>>>>>>>+ >>>+ * .                  ; , (44 = 00101100)
>>>>>>>>+ * .                       ; space (32 = 00100000)
>>>>+ >>>>>>+ >>>>>>+ >>>+ * .      ; W (87 = 01010111)
>>>>+ >>>>+ >>>+ >>>>>>+ * .        ; o (111 = 01101111)
>>>>+ >>>>+ >>>>>>+ >>>+ * .        ; r (114 = 01110010)
>>>>+ >>>>+ >>>>>>+ * .             ; l (108 = 01101100)
>>>>+ >>>>+ >>>+ >>>>>>+ * .        ; d (100 = 01100100)
>>>>>>>>+ >>>>>>+ >>>>>>+ * .       ; ! (33 = 00100001)
```
