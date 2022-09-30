# $$\color{blue}\boxed{\color{red}\mathbb{ESTUDOS \space DE \space PROGRAMAÇÃO \space PARALELA}}$$

## Acesso ao servidor da PUCRS

---

1. Abrir o CMD e digitar:

```shell
ssh portoalegre\matricula@sparta.pucrs.br
```

**matricula** deve ser o seu código de matricula da PUCRS

Ele vai pedir para confirmar se deseja fazer essa conexão, só escrever no console **yes**

Ele vai pedir uma senha, essa senha é a sua senha de acesso aos computadores e internet da PUCRS

---

## Acesso ao servidor GRAD

---

Servidor $\mathbb{\color{orange}GRAD}$ é um servidor para rodar programas paralelos dentro do laboratório da PUCRS, podemos acessar ele direto pelos computadores dentro da PUCRS ou podemos acessar ele utilizando o $\mathbb{\color{green}SPARTA}$ mostrado como acessar mais acima.

Para acessar o $\mathbb{\color{orange}GRAD}$ devemos utilizar o seguinte comando dentro do $\mathbb{\color{green}SPARTA}$ ou direto no console na PUCRS:

```shell
ssh -o PasswordAuthentication=yes usuarioGRAD@grad.lad.pucrs.br
```

**usuarioGRAD** é um código que o professor da cadeira de Programação Paralela passa no inicio do semestre, que foi pedido para a PUCRS termos um usuário durante do semestre.

Com isso estamos dentro do sistema $\mathbb{\color{orange}GRAD}$ da PUCRS.
