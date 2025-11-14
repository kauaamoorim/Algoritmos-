Cadastro e Avaliação de Estudante em C

Projeto simples desenvolvido em linguagem C com o objetivo de praticar o uso de struct, funções de entrada e saída, manipulação de strings e estruturas condicionais.

Funcionalidades do Programa
Tipo	Descrição
Cadastro	Lê nome, matrícula e duas notas do estudante
Cálculo	Calcula a média aritmética das notas
Exibição	Mostra nome, matrícula, notas e média calculada
Avaliação	Determina se o aluno foi aprovado ou reprovado (média ≥ 6)
Recursos e Funções Utilizadas
Função	Descrição
fgets()	Lê o nome completo do aluno, incluindo espaços
strcspn()	Remove o caractere \n deixado pelo fgets()
if/else	Define a aprovação ou reprovação com base na média
struct Estudante	Agrupa os dados: nome, matrícula, notas e média
Tecnologias e Recursos Utilizados

Desenvolvido em C utilizando Visual Studio Code, Dev-C++ e compiladores como GCC e GDB Online.

Bibliotecas utilizadas
#include <stdio.h>    // Entrada e saída de dados
#include <string.h>   // Manipulação de strings

Estrutura principal (struct Estudante)
struct Estudante {
    int matricula;
    float nota1;
    float nota2;
    float media;
    char nome[50];
};

Instalação, compilação e execução

Para executar o programa, é necessário utilizar um compilador de C ou algum compilador online.

Compilando em uma IDE

Baixar o arquivo aluno.c

Abrir o arquivo na IDE

Compilar e executar

Clonando o código

Abra o terminal e execute:

git clone https://github.com/SEU-USUARIO/seu-repositorio.git


Acesse a pasta do projeto:

cd seu-repositorio


Abrindo no VS Code:

code .

Adicionando avisos ao compilador (Wall e Wextra)

Recomenda-se o uso das flags para melhorar a qualidade do código:

gcc -Wall -Wextra aluno.c -o aluno.exe


Wall: ativa avisos importantes

Wextra: ativa avisos adicionais e mais rigorosos

Execução

Após compilar, execute:

./aluno.exe

Exemplo de uso
Entrada
Digite o nome do aluno: Ana Pereira
Digite a matricula: 102030
Informe a primeira nota: 7.5
Informe a segunda nota: 6.0

Saída
--- Dados do Aluno ---
Nome: Ana Pereira
Matricula: 102030
Nota 1: 7.5
Nota 2: 6
Média: 6.75
Aluno(a) Ana Pereira aprovado!

Informações adicionais

Este projeto foi desenvolvido com a intenção de praticar:

Estruturas condicionais

Estruturas de dados (struct)

Manipulação de strings

Entrada e saída de dados

Organização de código em C

Contribuições para melhoria do código são bem-vindas.
