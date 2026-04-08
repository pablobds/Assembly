um registrador é um conjunto de 32bits exemplos 
```
mov r0, #10 
```
> registrador r0 contem o numero 10 que em bits 00000000 00000000 00000000 00001010 

os registradores fica em CPU direto no hardware 
existe 15 registradores

| Registrador | Função |
| ----------- | ------ |
| r0 a r3 | argumentos e retorno |
| r4 a r11 | uso geral |
| r12 | temporario |
| r13(SP) | stack point | 
| r14(LR) | link register |
| r15(PC) | program counter |

pode usar r0 até a11 para uso geral 

---

Operadores 
----
contem 3 Operadores

| operador | Função |
| -------- | ------ |
| mov | copia e altera |
| add | soma |
| sub | subtrai | 


- Mov

mov copia ou altera 

exemplos 
```
mov r0, #1
```
agora o registrador `r0` está com numero 1

mas se você reutilizar esse mesmo registrador `r0` e alterar para 5

```
mov r0, #5
```

agora o registrador `r0` vai ficar com numero 5

- Add

para fazer uma soma você utiliza add 

vamos utilizar 2 registradores r0, r1 

```
mov r0, #5
mov r1, #5
```

agora `r0` está com numero 5 e o `r1` também 

vamos fazer uma soma entre eles 

e utilizar o `r2` para o resultado

```
add r0, r1, r2
```
> 5 + 5 = 10

agora a soma foi feita temos `r2` com a soma final de numero 10

---


