# Anotações aulas :memo:

## Curso: Ambiente de Desenvolvimento e Primeiros Passos com Python :computer::snake:

### Definindo o ambiente e primeiros passos com Python

**Introdução ao Python**

Python foi criada em 1989 pelo programador Guido Van Rossum. A ideia era dar continuidade a linguagem ABC desenvolvida no Centro de Pesquisa Holandês (CWI), essa era uma linguagem pensada para iniciantes devido a sua facilidade de aprendizagem e utilização. Ele quis continuar o projeto  como hobby  e seus objetivos para a linguagem Python eram:

* Uma linguagem fácil e intuitiva
* Código aberto, para que todos possam contribuir
* Código tão inteligível quanto o inglês.
* Adequadas para tarefas diárias, e produtiva!

**Linha do tempo do Python**

1989 - 1991: Guido Van Rossum inicia o desenvolvimento em 1989 e em 1991 lança a primeira versão pública (0.9.0).

1994: É lançada a versão 1.0 do Python

1995: Guido lança a versão 1.2 e encerra seu vínculo no centro de pesquisa CWI, criando então a **BeOpen Python Labs** (BeOpen.com) junto com a equipe dos principais desenvolvedores Python. 

2000 - 2001 : A segunda versão de Python é publicada junto com essa versão nasce a **List Comprehensions**. Em 2001 nasce a Python Software Foundation (PSF),  com isso a partir do Python 2.1 todo o código possui documentação e especificações de linguagem.

2008: É lançada a versão 3.0 com melhor performance e problemas de design solucionados, com isso mudanças profundas foram feitas fazendo com que o Python versão 3 não fosse retrocompatível (um código escrito em python 2 não roda em python bem como o contrário).

**Por quê?**

Python é uma linguagem versátil e possui as seguintes características:

* Tipagem dinâmica e forte (não é necessário definir o tipo da entrada ou dado : int, float)
* Multiplataforma e multiparadgima. (roda em linux, windows e etc... suporta vários paradigmas de programação: orientação a objetos, programação procedural e etc.. )
* Comunidade expressiva e ativa.
* Curva de aprendizado baixa. (fácil de aprender para quem está iniciando e fácil de se adaptar para quem já tem experiência).
* **Não** é recomendado para Mobile

**Configuração de ambiente de desenvolvimento**

link instalação Windows: http://python.org.br/instalacao-windows/

*python --version*: comando do terminal do windows  para ver se o Python está instalado

**IDE recomendada pelo prof**

**VSCode** pelos seguintes motivos: é gratuita, suporta múltiplas tecnologias e tem boa performance

No VsCode instalar as extensões: Python, autoDocstring e intelliCode

## Curso: Conhecendo a Linguagem de Programação Python :tongue::snake:

## :snake:

### Tipos de Dados

Os tipos de dados servem para definir as características  e os comportamentos de um valor (objeto) para o interpretador, ou seja o número (objeto) 10 é do tipo int e com ele eu consigo realizar operações matemáticas, outra caracterista é em relação ao armazenamento ou seja quanto de memória esse objeto irá consumir.

Os tipos padrões da linguagem são:

* Texto: str 
* Númerico: int , float , complex 
* Sequência: list, tupla, range
* Mapa: dict
* Coleção: set, fronzenset
* Booleano: bool
* Binário: bytes, betearray, memoryview

**Tipos de números**

Números inteiros:

São representados pela classe **int** e possuem precisão limitada. exe: 1,10,100,-1,-10,-100...

Números de ponto flutuante:

São usados para representar os números racionais e sua implementação é feita pela classe **float**. exe: 1.5, -10.543, 7.76...

Booleanos:

É usado para representar verdadeiro ou falso, e é representado pela classe **bool**. Em Python o tipo booleano é uma subclasse de **int**, uma vez que qualquer número diferente de 0 representa verdadeiro (true) e 0 falso (false).

**Strings**

São usadas para representar valores alfanuméricos, em Python as string são definidas utilizando a classe **str**. exe: "python", 'p', ""Python"".....

**Tipos de Dados representados no Python**

*int*: `print(11 + 1000)` = 1011

*float*: `print(1.5 + 1 +0.5)` = 3.0

*booleano*: 

`print(True) ` = True 

`print(False)` = False

*str*: `print('Python')` = Python

**Tipos de classes (construtores) no Python**

**int**()

**float**()

**bool**()

**str**()

### Modo Interativo

O interpretador Python pode executar em modo que possibilite o desenvolvedor a escrever código, e ver o resultado na hora. E isso pode ser feito de duas maneiras: 1ª escrevendo (python) no terminal ou 2ª executando o script com a flag -i (python -i app.py). exe:

entrada: `>>> 1 + 10`

saída: 11

entrada: `python -i Primeiro-programa.py`

saída: Olá, mundo!

**Funções dir e help**

**dir**

Sem argumentos, retorna a lista de nomes no escopo local atual. Com um argumento, retorna uma lista de atributos válidos para o objeto

sem argumentos: 

entrada: `>>> dir()`

saída: ['__annotations__', '__builtins__', '__doc__', '__loader__', '__name__', '__package__', '__spec__']

com argumentos:

entrada: `>>> dir(100)`

saída: ['__abs__', '__add__', '__and__', '__bool__', '__ceil__', '__class__', '__delattr__', '__dir__', '__divmod__', '__doc__', '__eq__', '__float__', '__floor__', '__floordiv__', '__format__', '__ge__', '__getattribute__', '__getnewargs__', '__gt__', '__hash__', '__index__', '__init__', '__init_subclass__', '__int__', '__invert__', '__le__', '__lshift__', '__lt__', '__mod__', '__mul__', '__ne__', '__neg__', '__new__', '__or__', '__pos__', '__pow__', '__radd__', '__rand__', '__rdivmod__', '__reduce__', '__reduce_ex__', '__repr__', '__rfloordiv__', '__rlshift__', '__rmod__', '__rmul__', '__ror__', '__round__', '__rpow__', '__rrshift__', '__rshift__', '__rsub__', '__rtruediv__', '__rxor__', '__setattr__', '__sizeof__', '__str__', '__sub__', '__subclasshook__', '__truediv__', '__trunc__', '__xor__', 'as_integer_ratio', 'bit_count', 'bit_length', 'conjugate', 'denominator', 'from_bytes', 'imag', 'numerator', 'real', 'to_bytes']

**help**

Invoca o sistema de ajuda integrado (documentação). É possível em modo interativo ou informar por parâmetro qual o nome do módulo, função, classe, método ou variável. Exemplo:

sem argumento: `>>> help()`

saída: permite pesquisa, exemplo: int ele retorna todos metódos.

com argumento: `>>> help(100)`

saída: retorna a classe, métodos...






