start:
		push 0xe54409d5
		push 0xe6cf51f0
		push 0xd2c26416
		call asm3
asm3:
        push   ebp
        mov    ebp,esp
        xor    eax,eax
        mov    ah,BYTE PTR [ebp+0x9]
        shl    ax,0x10
        sub    al,BYTE PTR [ebp+0xe]
        add    ah,BYTE PTR [ebp+0xf]
        xor    ax,WORD PTR [ebp+0x12]
        nop
        pop    ebp
        ret  

## Referencias 
https://carlosrafaelgn.com.br/Asm86/