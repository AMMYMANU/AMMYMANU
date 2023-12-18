.model small
.stack 
.data
cadena1 db 'Hola Mundo'


.code
programa:

mov ax,@data
mov ds,ax

mov dx, offset cadena1
mov ah,9
int 21h

end programa

ret
