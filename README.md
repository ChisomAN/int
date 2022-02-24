.data
Array : .word 134,232,76,52
.text
la $s4,Array
lw $t9, 8($s4)
lw $t8, 4($s4)
add $t8, $t9, $t8
sw $t8, 4($s4)
