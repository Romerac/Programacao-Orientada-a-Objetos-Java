# Atividade Prática
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)


Construa um projeto identificado por **prjLivro**. A partir da modelagem da classe **Livro** faça sua implementação na linguagem **Java**.

## Livro

```
- identificacao : int                     ---Identificação do Livro
- titulo : String                         ---Título do Livro
- situacao : boolean                      ---Situação do Livro: false - Disponível
                                                                true – Emprestado
                                          
- valMultaDiaria : double                 ---Valor a ser cobrado por dia em atraso na entrega do livro
```
```
+ Livro(int,String)                       ---Tem como parâmetro de entrada a identificação e o título do livro.
+ setValMultaDiaria(double):void
+ getIdentificacao() : int
+ getTitulo() : String
+ getSituacao() : boolean
+ emprestar() : void                      ---Empresta o livro mudando a situação do livro para emprestado (true).
+ devolver(int) : double                  ---Tem como parâmetro de entrada a quantidade de dias em atraso. Muda sua situação para 
                                             disponível (**false**). Calcula e devolve o valor a ser pago pela entrega em atraso 
                                             do livro.
```

---

Em seguida implemente, no respectivo projeto, uma aplicação (**Aplic.java**) que faça a instanciação de um objeto da classe **Livro** e em seguida faça a interação com o objeto instanciado de acordo com as opções do menu abaixo:
---
```
1 – Consultar livro
2 – Emprestar livro
3 – Devolver livro
4 – Sair

Digite a opção:
```

---

## Considerações

* As entradas de dados devem ser feitas utilizando a classe **Scanner**.
* Na operação **Consultar livro** deve ser exibido a identificação e o título do livro bem como sua situação (**Disponível** ou **Emprestado**).
* Caso ocorra a tentativa de **emprestar um livro que se encontra emprestado** a aplicação deve exibir a seguinte mensagem: **“O livro está emprestado”**.
* Caso ocorra a tentativa de **devolver um livro que se encontra disponível** a aplicação deve exibir a seguinte mensagem: **“O livro já está disponível”**.
* Na operação de **Emprestar livro** exibir a mensagem **“Operação de empréstimo realizada com sucesso”**.
* Na operação **Devolver livro** exibir a mensagem **“Operação de devolução realizada com sucesso”**. Caso ocorra, o valor da multa a ser pago pela entrega em atraso do livro deve ser exibido.

## Estrutura do Projeto

```
prjRetangulo/
│
├── Livro.java
└── Aplic.java
```
## Autores

- [@romerac](https://www.github.com/romerac)



