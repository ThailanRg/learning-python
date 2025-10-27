# Python

https://cursos.alura.com.br/formacao-data-science-python

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

03) Complexo (complex)
Tipo de dado usado para representar números complexos, normalmente em cálculos geométricos e científicos.

Um tipo complexo contém duas partes: a parte real e a parte imaginária, sendo que a imaginária contém um j no sufixo.

Com a função complex() podemos converter reais em números complexos. Ela traz dois argumentos, sendo o primeiro deles um número real, correspondente à parte real do número complexo, e o outro, um argumento opcional, que representa a parte imaginária. Por exemplo: z = complex(x,y).

No exemplo abaixo, vemos as variáveis, a e b, com os valores 10+16j e 3+80j atribuídos a elas.

Se pedirmos que o programa imprima o tipo das variáveis, vamos ter como retorno que elas são do tipo complex:

a = 10+16j
b = 3+80j
print(type(a))
print(type(b))
<class ‘complex’>
<class ‘complex’>
```
```
String (str);
Exemplo: hello

04) String (str)
É um conjunto de caracteres geralmente utilizados para representar palavras, frases ou textos.

Temos como exemplo as variáveis nome e profissão, com os dados Guilherme e Engenheiro de Software atribuídos a elas.

Pedindo para o programa imprimir o tipo dessas variáveis, teremos como retorno que elas são strings:

nome = ‘Guilherme’
profissao = ‘Engenheiro de Software’
print(type(profissao ))
print(type(nome))
<class ‘str’>
<class ‘str’>
```
```
Boolean (bool);
Exemplo: true / false

05) Boolean (bool)
Tipo de dado lógico que pode representar apenas dois valores: falso ou verdadeiro (False ou True, em Python).

Na lógica computacional, podem ser considerados como 0 ou 1.
Como exemplo, temos as variáveis: sexta_feira e feriado, com os dados True e False atribuídos a elas.

Se pedirmos que o programa imprima o tipo das variáveis, vamos ter como retorno que elas são do tipo boolean:

sexta_feira = True
feriado = False
print(type(sexta_feira))
print(type(feriado))
<class ‘bool’>
<class ‘bool’>
```

```
List (list);
Exemplo: ['Mônica', 'Ana', 'Bruno', 'Alice']

06) Listas (list)
As listas agrupam um conjunto de elementos variados, podendo conter: inteiros, floats, strings, outras listas e outros tipos.

Elas são definidas utilizando-se colchetes para delimitar a lista e vírgulas para separar os elementos. Já existe um artigo sobre listas em Python:
[operações básicas na plataforma](https://www.alura.com.br/artigos/listas-no-python), caso você queira se aprofundar no tema.

No código abaixo, por exemplo, vemos as variáveis alunos e notas, com os dados: ’Mônica’, ’Ana’, ’Bruno’, ’Alice’ e 10, 8.5, 7.8, 8.0 atribuídos a elas.

Pedindo para o programa imprimir o tipo das variáveis, vamos ter como retorno que elas são do tipo lista:

alunos = [‘Mônica’, ‘Ana’, ‘Bruno’, ‘Alice’]
notas = [10, 8.5, 7.8, 8.0]
print(type(alunos))
print(type(notas))
<class ‘list’>
<class ‘list’>
```
```
Tuple;
Exemplo: (90, 79, 54, 32, 21)

07) Tuplas (tuple)
Assim como as listas, a tupla é um tipo que agrupa um conjunto de elementos.

Porém, sua forma de definição é diferente, já que utilizamos parênteses e as informações são separadas por vírgula.

Mas a *principal diferença das listas é que as tuplas são imutáveis, ou seja, após sua definição, não podem ser modificadas.

Para saber mais a respeito desse tipo, confira o artigo [“Conhecendo as tuplas no Python”](https://www.alura.com.br/artigos/conhecendo-as-tuplas-no-python).

No exemplo abaixo, há as variáveis valores e pontos, com conjuntos de dados atribuídos a elas.

Pedindo para o programa imprimir o tipo das variáveis, temos como retorno que elas são do tipo tuple.

valores = (80, 29, 45, 91, 23)
pontos = (10, 29.05, 66.8, 72)
print(type(valores)
print(type(pontos))
<class ‘tuple’>
<class ‘tuple’>
Se tentarmos modificar uma tupla, receberemos a seguinte mensagem de erro:

IDE Jupyter Notebook exibindo o retorno”TypeError: ‘tuple’ object does not support item assignment

```
```
Dictionary (dic);
Exemplo: {'Camila': 1.65, 'Larissa': 1.60, 'Guilherme': 1.70}

08) Dicionários (dict)
Os dicionários são normalmente utilizados para agrupar elementos através da estrutura de chave e valor, de forma que a chave é o primeiro elemento, seguido por dois pontos e pelo valor.

Vemos abaixo um exemplo de seu uso, por meio de variáveis de altura e idade, com dados de pessoas como primeiro elemento e os respectivos dados referentes às alturas e idades como valores.

altura={‘Sandra’:1.65, ‘Elizabeth’: 1.60, ‘Roberto’: 1.70}
idade = {‘Sandra’:35, ‘Elizabeth’:58, ‘Roberto’:68}”
print(type(altura)
print(type(idade))
<class ‘dict’>
 <class ‘dict’>
```

## Conversao de tipos

Float para String
```
# Antes de converter
altura=1.55
print(type(altura)

# Fazendo a conversão
altura = str(altura)”

# Depois da conversão
print(type(altura) 
print(altura)

<class ‘float’>
<class ‘str’>
```

Inteiro para Float

```
# Antes de converter
idade=18
print(type(idade))

# Fazendo a conversão
idade = float(idade)

# Depois da conversão
print(type(idade) 
print(idade)

<class ‘intt’>
<class ‘float’>
```

## Estruturas condicionais em Python: if, elif e else

Estruturas condicionais são artifícios utilizados para controlar o fluxo de execução de programas, assim podemos determinar qual bloco de código será executado a partir de uma determinada condição.

Na linguagem Python, podemos fazer isso utilizando as estruturas if, elif e else, como veremos a seguir.

> ### If

Utilizamos o if em um programa quando pretendemos verificar se uma ação é verdadeira e executar o bloco de código contido em seu escopo.

Fazemos isso da seguinte forma:

```
media = 7
if media > 6.9:
print(“Você foi aprovado)”
```

Neste exemplo, nosso programa irá executar e retornar a mensagem: “Você foi aprovado”, apenas se a variável media possuir um valor maior que 6.9. Caso o valor seja menor do que isso, ele simplesmente irá ignorar o comando ''print'' e finalizará logo em seguida.


> ### Else

Se usarmos o if/else em conjunto, faremos com que uma das ações presentes no código sejam executadas, pois se determinada condição (if) for verdadeira, o programa executará uma ação.

Caso não seja verdadeira, executaremos o else, ou seja, outra ação. Desse modo, testamos se uma condição é verdadeira.

Neste exemplo abaixo, nosso programa irá executar e retornar a mensagem: “Você foi reprovado”, apenas se a variável media possuir um valor menor que 4.9. Caso contrário, será printado: “Você foi aprovado”.

```
media = 5

if media < 4.9:
print(“Você foi reprovado”)
else:
    print(“Você foi aprovado”)

```

> If, elif e else

Utilizamos if/elif/else quando precisamos verificar mais de uma condição. Imagine que precisamos verificar se um aluno foi reprovado ou se ele ficou de recuperação.

Teríamos algo parecido com o seguinte cenário:

```
media = 6
if media < 5
print(“Você foi reprovado”)
elif media > 5 
media < 7
    print(“Você fará a recuperação”)
else:
    print(“Você foi aprovado”)
```

Primeiro, precisamos verificar se a média do aluno é menor que 5.

Em caso positivo, vamos imprimir a mensagem: “Você foi reprovado”. Caso essa condição seja falsa, precisamos verificar se ele foi aprovado ou se fará a recuperação.


Para isso, o elif irá testar se a média está entre os valores 5 e 7. Se sim, vamos imprimir a mensagem: “Você fará a recuperação”. Se a condição do if e do elif forem falsas, o código contido no else será executado e imprimirá a mensagem: “Você foi aprovado”.

## Estrutura Match

A partir do Python 3.10, podemos utilizar a estrutura match, que é uma maneira mais organizada e legível para lidar com múltiplas condições. Ela nos permite combinar padrões e executar o bloco de código correspondente ao primeiro padrão que for verdadeiro.

```
media = 6

match media:
    case media if media < 5:
        print("Você foi reprovado")
    case media if 5 <= media < 7:
        print("Você fará a recuperação")
    case media if media >= 7:
        print("Você foi aprovado")

```

O trecho primeiro verifica a media e avalia cada caso para determinar qual bloco de código executar, da seguinte forma:

- O primeiro case verifica se a média é menor que 5 e, se isso for verdadeiro, imprime "Você foi reprovado".

- O segundo case verifica se a média está entre 5 e 7 (inclusive) e, se isso for verdadeiro, imprime "Você fará a recuperação".

- O terceiro case verifica se a média é maior ou igual a 7 e, se isso for verdadeiro, imprime "Você foi aprovado".

- Se nenhuma das condições for satisfeita, o match não executa nenhum bloco de código, mas podemos adicionar um case como padrão para lidar com casos que não prevemos.

<br>

Embora a estrutura match em Python não seja exatamente uma estrutura condicional no sentido tradicional como if, elif, e else, ela serve para controlar o fluxo do programa com base em diferentes condições e padrões

Estruturas de repetição Python: for e while
As estruturas de repetição são utilizadas quando queremos que um bloco de código seja executado várias vezes. Em Python podemos fazer isso de duas formas: utilizando for ou while.

## Como usar For no Python?
Utilizamos o for quando queremos iterar sobre um bloco de código por um determinado número de vezes.


```
for i in range(1,10):
    print(i)

Saída:

1
2
3
4
5
6
7
8
9

```

## Como usar o While no Python?

A outra forma de repetir a execução de um trecho de código até que uma condição seja satisfeita é utilizar o while.

Ou seja, é necessário que uma expressão booleana dada seja verdadeira. A partir do momento que ela se tornar falsa, o while para.

```
gastos=0
valor_gasto=0

while gastos < 1000
    valor_gasto = int(input(“Digite o valor gasto”))
    gastos = gastos + valor_gasto
print(gastos)

Digite o valor do novo gasto 20
Digite o valor do novo gasto 500
Digite o valor do novo gasto 480
1000

```

## Boas Práticas de programação em Python

Com a constante evolução da tecnologia sempre surgem novas formas de escrever um código.

Por isso, aplicar boas práticas de programação é fundamental para aprimorar o ambiente de trabalho, ter qualidade no momento de programar, manter o código legível, organizado e funcional.

[Como desenvolver boas práticas de programação? com Fabio Akita | #HipstersPontoTube](https://www.youtube.com/watch?v=GUanHEGlje4)

[fonte](https://www.alura.com.br/artigos/python)


## Módulos e bibliotecas em Python

## Data

Lib para data

https://www.alura.com.br/artigos/lidando-com-datas-e-horarios-no-python

## PYPI Python Package Index

PyPI O Python Package Index, abreviado como PyPI é o repositório de software oficial de terceiros para Python.

De acordo com a documentação oficial:

“PyPI é o Índice de Pacotes padrão para a comunidade Python. Está aberto a todos os desenvolvedores Python para consumir e distribuir suas distribuições.”

Alguns gerenciadores de pacotes, incluindo o pip, usam o PyPI como a fonte padrão para os pacotes e suas dependências, e mais de 113.000 pacotes Python podem ser acessados por meio do PyPI.

O PyPI, primariamente, hospeda pacotes Python na forma de arquivos pré-compilados e funciona como um índice.

Assim, ele permite que os usuários e usuárias pesquisem e criem pacotes por meio de palavras-chave ou por filtros que ficam disponíveis com licença de software livre.

Para saber mais sobre o PyPI você pode consultar o artigo “Como publicar seu código Python no PyPI”

[fonte](https://www.alura.com.br/artigos/python)

## Ambientes virtuais
Normalmente, aplicações em Python usam pacotes e módulos que não vêm como parte da instalação padrão.

Algumas aplicações podem precisar de uma versão específica de uma biblioteca caso seja necessária a resolução de algum problema em particular, ou ainda, se o software foi desenvolvido utilizando-se de uma versão obsoleta da interface da biblioteca.

Isso significa que talvez não seja possível uma instalação Python preencher todos os requisitos necessários.

Se uma aplicação “A” necessita da versão 1.0 de um módulo particular, mas a aplicação “B” necessita da versão 2.0, os requisitos entrarão em conflito e instalar qualquer uma das duas versões fará com que uma das aplicações não seja executada.

A solução para esse problema é criar um ambiente virtual, uma árvore de diretórios que contenha uma instalação Python para uma versão particular do Python, além de uma série de pacotes adicionais.

Para aprender mais sobre esses ambientes, leia o artigo Python: Venv e Poetry para criar ambientes virtuais.

[fonte](https://www.alura.com.br/artigos/python)


## Python e Inteligência Artificial

Python é uma das linguagens de programação mais versáteis e poderosas para trabalhar com inteligência artificial (IA).

Uma das maiores vantagens de usar Python para IA é a disponibilidade de bibliotecas que facilitam a construção de modelos de aprendizado de máquina e deep learning. Algumas das bibliotecas mais populares incluem:

Scikit-learn: ideal para tarefas de aprendizado de máquina tradicionais, como classificação, regressão e clustering. É fácil de usar e possui uma vasta gama de algoritmos.
TensorFlow e Keras: utilizadas principalmente para deep learning. TensorFlow, desenvolvido pelo Google, é uma biblioteca para construir e treinar redes neurais.
Keras oferece uma interface de alto nível que facilita o desenvolvimento de modelos complexos. A biblioteca pode ser executada em conjunto com o Tensorflow.

PyTorch: desenvolvido pelo Facebook, é outra biblioteca popular para deep learning, especialmente em pesquisa acadêmica. É conhecido pela sua flexibilidade e facilidade de uso.
Além de criar seus próprios modelos, você também pode utilizar APIs de empresas especializadas em IA para acessar recursos avançados sem precisar construir tudo do zero. Um exemplo notável é a OpenAI, que oferece uma API para IA generativa.

A API da OpenAI permite integrar capacidades avançadas de processamento de linguagem natural (NLP) em suas aplicações. Com a API, é possível realizar tarefas como geração de texto, tradução, resumo e muito mais, utilizando modelos treinados por especialistas em IA.


## Quais são as Bibliotecas e Frameworks mais utilizados?

Algumas das bibliotecas e frameworks mais utilizados em Python são:


> NumPy

Para computação numérica, permite a manipulação de arrays multidimensionais e funções matemáticas de alto desempenho.

> Pandas

Para manipulação e análise de dados, fornece estruturas de dados flexíveis e eficientes para trabalhar com dados tabulares.

> Matplotlib

Para criação de gráficos e visualizações de dados em Python.

> TensorFlow

Framework de aprendizado de máquina de código aberto para desenvolver e treinar modelos de aprendizado profundo.

> Django

Framework web de alto nível que facilita o desenvolvimento rápido e seguro de aplicativos web.

> Flask

Framework web leve e flexível para a criação de aplicativos web em Python.

> SciPy

Biblioteca para computação científica que fornece funcionalidades para otimização, interpolação, processamento de sinais, álgebra linear e muito mais.

> Scikit-learn

para aprendizado de máquina, fornece algoritmos de classificação, regressão, clustering e pré-processamento de dados.

> BeautifulSoup

para extração de dados de páginas web, permitindo a raspagem de dados de forma fácil e eficiente.

> Requests

para fazer requisições HTTP de maneira simples e fácil, muito útil para acessar APIs e baixar conteúdo da web.


> Pillow

para processamento de imagens, oferece funcionalidades para abrir, manipular e salvar muitos formatos de arquivos de imagem.

> Asyncio

para programação assíncrona, permite escrever código concorrente usando a estrutura de async/await, facilitando a execução de operações de I/O de forma eficiente.

> Tkinter

biblioteca padrão do Python para a criação de interfaces gráficas (GUI), permitindo o desenvolvimento de aplicativos desktop com uma variedade de widgets.





