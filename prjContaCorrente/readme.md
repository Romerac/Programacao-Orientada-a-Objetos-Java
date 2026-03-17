
# Exercício – Classe Retângulo em Java
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

## Descrição:
Neste exercício foram implementados os métodos `getAltura()` e `getBase()`.  
Esses métodos pertencem à categoria de **métodos de acesso (getters)**, cuja finalidade é **retornar o valor armazenado em um atributo da classe**.

Assim, o método `getAltura()` retorna o valor do atributo `altura`, enquanto `getBase()` retorna o valor do atributo `base`. Dessa forma, é possível consultar essas informações do objeto de maneira organizada e controlada, sem acessar diretamente os atributos da classe.

Seguindo o princípio de **encapsulamento**, no qual os atributos da classe são acessados por meio de métodos definidos na própria classe.


## Modelagem da Classe


ContaCorrente
```
- numero : int                                          ---Número da conta
- saldo  : double                                       ---Saldo da conta
```
```
+ ContaCorrente(int, double)                            ---Construtor: Recebe como parâmetros o número da conta e o saldo inicial 
                                                           da conta corrente.
+ getNumero() : int                                     ---Retorna o número da conta
+ getSaldo() : double                                   ---Retorna o saldo atual da conta
+ sacar(double) : void                                  ---Recebe como parâmetro o valor do saque que deve ser subtraído do saldo da conta
+ depositar(double) : void                              ---Recebe como parâmetro o valor do depósito, que deve ser 
                                                           adicionado ao saldo da conta
```

---

# Exercício:

"De acordo com a especificação da classe **ContaCorrente**, faça sua implementação em **Java** e em seguida implemente uma aplicação (`Aplic.java`) que faça a **instanciação de um objeto da classe ContaCorrente**.

Após a criação do objeto, foi feita a interação com o usuário utilizando o seguinte menu:

```
1 – Depositar
2 – Sacar
3 – Consultar Saldo
4 – Sair

Digite a opção:
```

---

# Considerações

- Defina o projeto com o nome **prjContaCorrente**.
- Utilize a classe **Scanner** para realizar as entradas de dados.
- Nas operações de **depósito, saque e consulta**, deve ser exibido o **número da conta**.
- Na operação de **saque**, caso seja informado um valor **superior ao saldo da conta**, exibir a mensagem: **"Saldo Insuficiente!"**

## Estrutura do Projeto

```
prjRetangulo/
│
├── ContaCorrente.java
└── Aplic.java
```
## Autores

- [@romerac](https://www.github.com/romerac)


