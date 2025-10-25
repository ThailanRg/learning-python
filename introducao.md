# Python

## Origem

O desenvolvimento do Python aconteceu, inicialmente, pelo programador holandês Guido van Rossun, no final da década de 1980.

Mas sua primeira versão foi lançada só em 1991 no Centrum Wiskunde & Informatica — CWI (Instituto Nacional de Pesquisa para Matemática e Ciência da Computação), na Holanda.

A linguagem fez grandes avanços para o desenvolvimento de código aberto, utilizando as [PEPs](https://peps.python.org/pep-0000/) (“Propostas de Enriquecimento do Python”) como principal ferramenta para sugestões de melhoramento e discussões da comunidade.

As Propostas de Enriquecimento do Python funcionam para descrever mudanças na linguagem ou em suas normas.

O público pode avaliá-las e aceitá-las e rejeitá-las, depois de muitas discussões. Qualquer pessoa pode escrever e enviar uma PEP para avaliação.

## Por que o Python é tão importante? — entenda por que aprender a programar em Python

De acordo com a pesquisa [Python Developers Survey 2023 Results](https://www.jetbrains.com/lp/devecosystem-2023/python/), realizada pela JetBrains, o Python é umas das linguagens que mais crescem em relevância e valorização pelas empresas.

## Proposta

Python é uma linguagem geral, que não é especializada em nenhum problema específico.

O próprio programa “reconhece” qual tipo de dado está sendo utilizado, fazendo com que ele não precise ser previamente declarado. Por isso dizemos que ele possui uma semântica dinâmica.

O Python é utilizado para desenvolvimento de software, análise de dados, inteligência artificial, automação de tarefas, criação de aplicativos web e daí por diante.

[fonte](https://www.alura.com.br/artigos/python)

## Linguagem interpretada
O fato de ser uma linguagem interpretada, o que significa que ela não precisa passar pelo processo de compilação.

O processo de interpretação é executado dentro de máquinas virtuais, nas quais o código passa por uma camada intermediária que irá traduzir os comandos de programa para código binário.

Isso acelera bastante a velocidade de desenvolvimento.

[fonte](https://www.alura.com.br/artigos/python)

## Multiparadigma
Ela é um multiparadigma, pois nos dá a possibilidade de programar em vários paradigmas, tais como:

- Procedural 
    - Com instruções transmitidas ao computador na sequência em que devem ser executadas;
- Funcional
    - Paradigma que consiste em programas construídos aplicando e compondo funções;
- Orientação a objetos
    - Que traz a perspectiva do mundo real para a programação, tornando os programas fáceis de entender devido a essa relação.

## Primeiros passos
Instalar python

1 - [Baixar o instalador](https://www.python.org/downloads/release/python-3139/)

2 -  Marque a opção “Add Python to PATH”;
Clique em “Install Now”;

3 - Após a instalação, basta clicar no botão “Close”;
Para verificar se a instalação do Python foi bem-sucedida, pesquise no Menu Iniciar por “cmd” e clique duas vezes para abri-lo;

4 - Execute o comando para certificar que o python foi instalado, se tudo estiver certo o terminal ira imprimir a versao 

instalada.
```
python --version
```

5 - execute o comando para validar se o gerenciador de pacotes do python tambem foi instalado

```
pip --version
```

<br>

# Quais são os tipos de dados em Python?
Python é uma linguagem dinamicamente tipada, o que significa que não é necessário declarar o tipo de variável ou fazer casting (mudar o tipo de variável), pois o Interpretador se encarrega disso para nós.

Isso significa também que, se por algum motivo precisarmos alterar o tipo de variável durante a execução do programa, é possível fazer essa mudança.

Os tipos de dados padrão do Python são:

```
Inteiro (int);
Exemplo: 1

01) Tipo Inteiro (int)
É um tipo usado para um número que pode ser escrito sem um componente decimal, podendo ser positivo ou negativo.

No código abaixo, por exemplo, vemos as variáveis, idade e ano, com os valores 20 e 2010 atribuídos a elas; se pedirmos que o programa imprima o tipo das variáveis, teremos como retorno que elas são do tipo inteiro:

idade = 20
ano = 2010
print(type(idade))
print(type(ano))
<class ‘int’>
<class ‘int’>
```
```
Ponto Flutuante ou Decimal (float);
Exemplo: 1.1

02) Ponto Flutuante ou Decimal (float)
É um tipo composto por números decimais. O float é usado para números racionais (que podem ser representados por uma fração), informalmente conhecidos como “números quebrados”.

No código abaixo, por exemplo, vemos as variáveis altura e peso com os valores 1.73 e 78.500 atribuídos a elas.

Se pedirmos que o programa imprima o tipo das variáveis, teremos como retorno que elas são do tipo float:

altura = 1.73
peso = 78.500
print(type(peso))
print(type(altura))
<class ‘float’>
<class ‘float’>
```
```
Tipo Complexo (complex);
Exemplo: 8j
```
```
String (str);
Exemplo: hello
```
```
Boolean (bool);
Exemplo: true / false
```
```
List (list);
Exemplo: ['Mônica', 'Ana', 'Bruno', 'Alice']
```
```
Tuple;
Exemplo: (90, 79, 54, 32, 21)
```
```
Dictionary (dic);
Exemplo: {'Camila': 1.65, 'Larissa': 1.60, 'Guilherme': 1.70}
```
