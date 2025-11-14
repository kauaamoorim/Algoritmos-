Sistema de Cadastro e Avaliação de Estudante (C)

Este projeto é um programa simples em linguagem C que permite cadastrar um estudante, calcular sua média e informar automaticamente se ele foi aprovado ou reprovado com base nas notas fornecidas.

 Funcionalidades

Entrada do nome, matrícula e duas notas do estudante.

Cálculo automático da média aritmética.

Exibição completa dos dados informados.

Verificação da situação:

Aprovado (média ≥ 6)

Reprovado (média < 6)

Conceitos Utilizados
struct

Usado para agrupar todas as informações relacionadas ao estudante.

fgets()

Permite ler o nome completo, incluindo espaços.

strcspn()

Remove o \n adicionado automaticamente pelo fgets().

Estrutura condicional if

Define a aprovação de acordo com a média calculada.

Estrutura do Código

O programa utiliza a seguinte estrutura para armazenar os dados:

struct Estudante {
    int matricula;
    float nota1;
    float nota2;
    float media;
    char nome[50];
};

Como Compilar e Executar
Compilação

No terminal, digite:

gcc main.c -o aluno

Execução
./aluno

Exemplo de Uso
Digite o nome do aluno: Maria Silva
Digite a matricula: 2023101
Informe a primeira nota: 8.5
Informe a segunda nota: 7.0

--- Dados do Aluno ---
Nome: Maria Silva
Matricula: 2023101
Nota 1: 8.5
Nota 2: 7
Média: 7.75
Aluno(a) Maria Silva aprovado!

Licença

Este projeto é livre para uso educacional.
