# Libft

## Descrição

Libft é a minha primeira biblioteca personalizada em C. Este projeto envolve a recriação de diversas funções da biblioteca padrão da linguagem C, além da implementação de funções adicionais que serão úteis para futuros projetos. O objetivo é aprofundar o conhecimento sobre manipulação de strings, memória dinâmica e listas encadeadas.

## Estrutura do Projeto

O projeto está organizado nos seguintes componentes:

- **Parte 1 - Reimplementação de funções da Libft**
- **Parte 2 - Funções adicionais**
- **Bônus - Manipulação de listas encadeadas**

## Funcionalidades

### Parte 1 - Funções da Libft

Reimplementação de funções comuns da biblioteca padrão C, todas com o prefixo `ft_`, incluindo:

- ft\_isalpha, ft\_isdigit, ft\_isalnum, ft\_isascii, ft\_isprint
- ft\_strlen, ft\_memset, ft\_bzero, ft\_memcpy, ft\_memmove
- ft\_strlcpy, ft\_strlcat, ft\_toupper, ft\_tolower
- ft\_strchr, ft\_strrchr, ft\_strncmp, ft\_memchr, ft\_memcmp
- ft\_strnstr, ft\_atoi
- ft\_calloc, ft\_strdup

### Parte 2 - Funções adicionais

Implementação de funções que auxiliam no manuseio de strings e memória, incluindo:

- ft\_substr, ft\_strjoin, ft\_strtrim, ft\_split
- ft\_itoa, ft\_strmapi, ft\_striteri
- ft\_putchar\_fd, ft\_putstr\_fd, ft\_putendl\_fd, ft\_putnbr\_fd

### Bônus - Manipulação de Listas Encadeadas

Para expandir as funcionalidades da biblioteca, foram incluídas funções para manipulação de listas encadeadas:

- ft\_lstnew, ft\_lstadd\_front, ft\_lstsize, ft\_lstlast
- ft\_lstadd\_back, ft\_lstdelone, ft\_lstclear
- ft\_lstiter, ft\_lstmap

## Como Usar

### Compilação

Para compilar a biblioteca, basta executar:

```sh
make
```

Isso gerará o arquivo `libft.a`.

### Uso em um Projeto

No uso do projeto, pode incluir a biblioteca usando:

```c
#include "libft.h"
```

## Regras do Projeto

- O código segue a Norm da 42.
- O `Makefile` contém as regras `all`, `clean`, `fclean`, `re` e `bonus`.
- Todas as alocações dinâmicas devem ser corretamente liberadas.
- Nenhuma variável global é permitida.
- Funções auxiliares devem ser declaradas como `static`.

## Autor

Pedro Cristóvão Veiga Correia

