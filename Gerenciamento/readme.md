Cadastro e Avaliação de Estudante em C

Projeto simples desenvolvido em linguagem C para praticar o uso de struct, entrada e saída de dados, manipulação de strings e estruturas condicionais.

| Tipo      | Descrição                                                |
| --------- | -------------------------------------------------------- |
| Cadastro  | Lê nome, matrícula e duas notas do estudante             |
| Cálculo   | Calcula a média aritmética das notas                     |
| Exibição  | Mostra nome, matrícula, notas e média                    |
| Avaliação | Informa se o aluno foi aprovado (média ≥ 6) ou reprovado |

| Recurso            | Descrição                             |
| ------------------ | ------------------------------------- |
| `fgets()`          | Lê o nome completo, incluindo espaços |
| `strcspn()`        | Remove o `\n` deixado pelo `fgets()`  |
| `if/else`          | Avalia aprovação ou reprovação        |
| `struct Estudante` | Agrupa os dados do aluno              |

Bibliotecas utilizadas
#include <stdio.h>    // Entrada e saída de dados
#include <string.h>   // Manipulação de strings

Estrutura utilizada 
struct Estudante {
    int matricula;
    float nota1;
    float nota2;
    float media;
    char nome[50];
};
Instalação, compilação e execução
Compilação:

Se estiver usando qualquer IDE (VS Code, Dev-C++, CodeBlocks, etc.):

Baixe o arquivo aluno.c

Abra na IDE

Compile e execute:

Compilação via terminal
gcc aluno.c -o aluno.exe

Execução:
./aluno.exe

Informações adicionais:

Este projeto foi desenvolvido para praticar conceitos fundamentais da linguagem C:
Estruturas (struct)\n
Entrada e saída de dados\n
Manipulação de strings\n
Estruturas condicionais
Organização e boas práticas na linguagem
Contribuições para melhoria do código são bem-vindas.
