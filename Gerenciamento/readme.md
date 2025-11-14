Cadastro e Avaliação de Estudante em C

Projeto simples desenvolvido em linguagem C para praticar o uso de struct, entrada e saída de dados, manipulação de strings e estruturas condicionais.

Funcionalidades
Tipo	Descrição
Cadastro	Lê nome, matrícula e duas notas do estudante
Cálculo	Calcula a média aritmética das notas
Exibição	Mostra nome, matrícula, notas e média
Avaliação	Informa se o aluno foi aprovado (média ≥ 6) ou reprovado
Recursos Utilizados
Recurso	Descrição
fgets()	Lê o nome completo, incluindo espaços
strcspn()	Remove o \n deixado pelo fgets()
if/else	Avalia aprovação ou reprovação
struct Estudante	Agrupa os dados do aluno
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
Compilação

Se estiver usando qualquer IDE (VS Code, Dev-C++, CodeBlocks, etc.):

Baixe o arquivo aluno.c

Abra na IDE

Compile e execute

Compilação via terminal
gcc aluno.c -o aluno.exe

Execução
./aluno.exe

Recomendações (Wall e Wextra)

Para ativar avisos do compilador:

gcc -Wall -Wextra aluno.c -o aluno.exe


-Wall: ativa avisos úteis

-Wextra: exibe avisos adicionais

Exemplo de uso
Entrada
Digite o nome do aluno: Marcos Oliveira
Digite a matricula: 556677
Informe a primeira nota: 8.5
Informe a segunda nota: 7.0

Saída
--- Dados do Aluno ---
Nome: Marcos Oliveira
Matricula: 556677
Nota 1: 8.5
Nota 2: 7
Média: 7.75
Aluno(a) Marcos Oliveira aprovado!

Informações adicionais

Este projeto foi desenvolvido para praticar conceitos fundamentais da linguagem C:

Estruturas (struct)

Entrada e saída de dados

Manipulação de strings

Estruturas condicionais

Organização e boas práticas na linguagem

Contribuições para melhoria do código são bem-vindas.
