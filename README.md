# 0x86

Hello World Again !, 0xa

```assembly

section .text
  global _start ; informa o linker (ld) qual é o ponto de entrada
_start:     ; ponto de entrada
mov ebx, 0  ; valor de retorno para o SO(Sistema Operacional)
mov eax, 1  ; valor da syscall exit()
int 0x80    ; chamando o kernel
```



![GDB>gef](https://repository-images.githubusercontent.com/188014223/adeee780-dfe9-11e9-83c4-0010d9155b49)
img source : https://github.com/topics/gef
