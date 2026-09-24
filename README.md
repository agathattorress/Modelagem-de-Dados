  Pet Care

Sistema de gerenciamento de uma loja de produtos e serviços para animais, desenvolvido em **Python**.

  Funcionalidades

* Visualização de produtos
* Visualização de animais para adoção
* Visualização de serviços
* Cadastro de clientes
* Agendamento de serviços
* Salvamento de agendamentos em arquivo `.txt`

   Requisitos

Para executar o projeto, é necessário ter:

* **Python 3** instalado
* O arquivo principal do programa (`.py`)
* O arquivo `dados.txt`

   Como executar

1. Instale o Python

2. Coloque os arquivos na mesma pasta

Por exemplo:

```text
Pet-Care/
├── main.py
├── dados.txt
└── README.md
```

O arquivo `dados.txt` é utilizado pelo programa para carregar os produtos, animais e serviços..

  Como usar o programa

Depois de executar o programa, será apresentado o menu principal:

```text
[1] Produtos
[2] Serviços
[3] Animais
[0] Sair
```

Digite o número da opção desejada e pressione **Enter**.

  1 - Produtos

Digite:

```text
1
```

O programa mostrará uma lista com os produtos disponíveis.

Por exemplo:

```text
Escolha um produto:
{'1': Ração, '2': Brinquedo, '3': Coleira}
```

Digite o número do produto que deseja consultar.

O programa exibirá informações como:

* Nome
* Descrição
* Preço
* Quantidade
* Categoria

Depois disso, aparecerá:

```text
[1] Prosseguir
[2] Voltar ao menu principal
```

Escolha `1` para prosseguir ou `2` para voltar ao menu.

  2 - Serviços

Digite:

```text
2
```

O programa mostrará os serviços disponíveis.

Escolha o número do serviço desejado para visualizar suas informações:

* Nome
* Descrição
* Preço
* Duração
* Categoria

Depois, escolha:

```text
[1] Prosseguir
[2] Voltar ao menu principal
```

Ao escolher **Prosseguir**, o programa solicitará os dados do cliente:

```text
Digite seu nome:
Digite seu telefone:
Digite seu email:
Digite seu endereço:
```

Depois será solicitado o agendamento:

```text
Digite uma data:
Digite um horário:
```

Após preencher todas as informações, o agendamento será criado e salvo.

  3 - Animais

Digite:

```text
3
```

O programa mostrará os animais disponíveis.

Escolha o número correspondente ao animal que deseja consultar.

Serão exibidas informações como:

* Nome
* Descrição
* Raça
* Idade
* Porte

Depois, escolha:

```text
[1] Prosseguir
[2] Voltar ao menu principal
```

Ao escolher `1`, o programa exibirá uma mensagem informando que o novo amigo está ansioso para conhecer seu novo lar.

  0 - Sair

Digite:

```text
0
```

O programa será encerrado.

  Arquivo `dados.txt`

O arquivo deve estar na **mesma pasta do programa**, pois ele é utilizado para carregar os dados.

Os dados são organizados nas seções:

```text
[PRODUTOS]

[ANIMAIS]

[SERVICOS]
```

As informações de cada registro são separadas por `;`.

  Importante

Não remova o arquivo `dados.txt` antes de executar o programa, pois ele é necessário para carregar os dados iniciais.

   Projeto

Projeto desenvolvido em Python utilizando **Programação Orientada a Objetos (POO)**.

 Pet Care — Cuidando dos seus melhores amigos.
