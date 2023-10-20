# PB-Compass-UOL
Este é um repositório para armazenar anotações e códigos criados ao longo do Programa de Bolsas Compass UOL.
![Logo Compass](https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/Logo_CompassoUOL_Positivo.png/800px-Logo_CompassoUOL_Positivo.png)

# Índice

- [PB-Compass-UOL](#pb-compass-uol)
- [Índice](#índice)
- [Sobre mim](#sobre-mim)
- [*SPRINT 1* | Resumo](#sprint-1--resumo)
    - [**Curso Git e GitHub**](#curso-git-e-github)
        - [Certificado do Curso: Git e GitHub](#certificado-do-curso-git-e-github)
    - [Curso Linux](#curso-linux)
      - [Comandos básicos](#comandos-básicos)
        - [Certificado do Curso: Linux](#certificado-do-curso-linux)
- [*SPRINT 2* | Resumo](#sprint-2--resumo)
    - [**Curso SQL para Análise de Dados**](#curso-sql-para-análise-de-dados)
        - [Certificado do Curso: SQL para Análise de Dados](#certificado-do-curso-sql-para-análise-de-dados)
    - [**Curso Big Data Fundamentos 3.0**](#curso-big-data-fundamentos-30)
        - [Certificado do Curso: Big Data Fundamentos 3.0](#certificado-do-curso-big-data-fundamentos-30)
- [*SPRINT 3* | Resumo](#sprint-3--resumo)
  - [**Curso Python 3 - Curso Completo do Básico ao Avançado**](#curso-python-3---curso-completo-do-básico-ao-avançado)
    - [Conclusão da Sprint 3](#conclusão-da-sprint-3)
- [*SPRINT 4* | Resumo](#sprint-4--resumo)
  - [**Curso Python 3 - Seção: programação funcional**](#curso-python-3---seção-programação-funcional)
  - [**Curso Docker para Desenvolvedores**](#curso-docker-para-desenvolvedores)
  - [**Curso Estatística Descritiva com Python**](#estatística-descritiva-com-python)
    - [Conclusão da Sprint 4](#conclusão-da-sprint-4)
- [*SPRINT 5* | Conclusão](#sprint-5)
- [*SPRINT 6* | Conclusão](#sprint-6)

- [**Cursos Complementares** | *Link para resumos*](#cursos-complementares--link-para-resumos)



# Sobre mim
Me chamo **Pedro Rodrigues Rocha**, tenho 18 anos e moro em Castilho/SP. Atualmente estou iniciando o 2° semestre do curso de **Sistemas de Informação** na *UFMS campus Três Lagoas*. Sou formado também como Técnico em Informática pelo *Instituto Federal de Mato Grosso do Sul (IFMS)*, e foi por meio desse curso que eu tive mais contato com a área de informática e tecnologia e me despertou mais interesse em seguir no ramo.
Em meu tempo livre eu gosto muito de ler livros e assistir filmes ou algo relacionado a esporte. 

![Foto pessoal](/img/profile.jpg)

# *SPRINT 1* | Resumo

### **Curso Git e GitHub**
![Logo Git](/img/git_icon.png) ![Logo GitHub](/img/github_icon.jpg)

- Controle de versão é um mecanismo para auxílio de gerenciamento de códigos-fontes, sendo o git o mais utilizado atualmente
- O git é baseado em repositórios que armazena as versões e cópias de cada desenvolvedor
- Os repositórios podem ir para servidores que servem para melhor gerenciamento, como o GitHub

**Principais comandos:**

> git init --> criação de um novo repositório  
git status --> verificar o estado que o projeto se encontra  
git add --> adicionar novos arquivos no projeto   
git commit --> salvar as alterações do projeto   
git push --> envia o código para o repositório remoto  
git pull --> atualiza o repositório local com o código disponível no repositório remoto   
git clone --> baixa um repositório de um servidor remoto    

**Comandos branch:**

> git branch --> visualiza os branchs disponíveis   
git branch < nome > --> criar um novo branch  
git checkout < nome > --> mudar para outro branch ("-b" também cria um novo e muda para ele)  
git merge < nome > --> unindo código de dois branches

**[Mais informações sobre comandos](Sprint-1/README.md#curso-gitgithub)** 

**Branches:** 
- Forma que o git separa versões dos projetos;
- Facilita a manutenção, testes e organização do projeto;

**Gist:**
- Pequenos blocos de códigos, armazenado no GitHub, que contém alguma solução interessante de algum problema;

**Markdown:**
- Forma para adição de estilos na web;
- Pode modificar o modo do texto, inserir links, imagens, trechos de código, entre outros, que contribui para uma melhor experiência para o usuário;
- **Títulos** são representados por **'#'**, de 1 a 6, modificando o tamanho do título;
- O __texto em negrito__ é representado por **dois '*'** ou __dois '_'__ nas extremidades do texto;
- O **_texto em itálico_** é representado por **_um '*'_ ou *um '_'*** nas extremidades do texto;
- Listas não ordenadas são feitas a partir de um '*' antes de cada item;
- Listas ordenadas são feitas a partir da numeração de cada item(1., 2., ...);
- A sintaxe de inserção de imagens é ![TextoAlt](link imagem);
- Sintaxe para links é [Texto do link](link do site);

##### Certificado do Curso: Git e GitHub

![Certificado Git e GitHub](Sprint-1/certificados/curso-git-github.jpg)

### Curso Linux 
![Logo Linux](img/linux_icon.png)

>**Terminal** é uma tela que executa o Shell. O **Shell** executa os comandos digitados.

**Diretórios:**
- *bin:* Contém arquivos binários;
- *boot:* Arquivos que auxiliam na inicialização do sistema;
- *dev:* Representa todos os arquivos de entrada e saída do sistema;
- *home:* Diretório de todos os usuários;
- *sbin:* Contém arquivos binários de inicialização do sistema;

#### Comandos básicos
>A sintaxe dos comandos podem se resumir em:   
**COMANDO -OPÇÕES ARQUIVOS/DIRETÓRIOS** <br>
-> Pode concatenar comando com o '&&' (*Ex: cd etc && ls*);<br>
-> Alguns comandos pode haver a combinação de parâmetos - (*Ex: ls -la (-l + -a)*);<br>
-> Alguns comandos suportam '*--help*' que mostra os parãmetros e suas funcionalidades;<br>
-> **ctrl + r** : busca de comandos utilizados anteriormente;

**Gerenciamento de diretórios e arquivos**

- **cd -->** Mudar de diretório;
- **ls -->** Lista os diretórios disponíveis;
- **clear -->** Limpa o terminal;
- **cat -->** Apresenta o conteúdo de arquivos;
- **touch -->** Cria novos arquivos e pode ser usado para alterar a data de alteração;
- **man -->** Mostra todas as informações dos comandos;
- **mkdir -->** Cria novos diretórios;
- **rm -->** Remoção de arquivos e diretórios;
- **rmdir -->** Só remove diretórios;
- **cp -->** Realiza a cópia de arquivos;
- **mv -->** Move arquivo;
- **pwd -->** Mostra qual o diretório atual;

**Gerenciamento de pacotes/aplicativos**

- **sudo -->** Possibilita atributos extras de propriedades do sistema;
- **apt-get -->** Gerenciamento de aplicativos (instala, atualiza, remove);

**Filtros e buscas de arquivos e diretórios**

- **head -->** Mostra o topo do arquivo;
- **tail -->** Mostra o fim do arquivo; 
- **grep -->** Busca por termos em um arquivo;
- **find -->** Busca por diretórios e arquivos;
- **locate -->** Busca o arquivo baseando-se na base de dados;
- **which -->** Mostra onde os comandos estão alocados;

**Editores de textos mais utilizados**

-  **nano -->** Abre o editor nano;<br>
-> *ctrl + o* : salva o arquivo;<br>
-> *ctrl + x* : fecha o editor;<br>
-> *nano [nome_arquivo]* : abre o arquivo para edição;<br>
-> *alt + a* : seleciona a área a ser copiada; <br>
-> *alt + 6* : copia a área selecionada; <br>
-> *ctrl + u* : cola; <br>
-> *ctrl + k*: recorta; <br>

- **vim -->** Abre o editor vim;<br>
-> *i* : modo de inserção;<br>
-> *:x* : salva e sai do arquivo;<br>
-> *vim [nome_arquivo]* : abre arquivo para edição;<br>
-> *:w* : salva sem sair do arquivo;<br>
-> *:q* : sair do arquivo;<br>

**Gerenciamento de usuários e grupos**

- **sudo adduser [nome] -->** Adiciona novos usuários;
- **sudo userdel --remove [nome] -->** Remove usuários;

>**Grupo** contém vários usuários, facilita gerenciamento de permissões.

- **getent group -->** Visualiza todos os grupos criados;
- **sudo groupadd -g [id] [nome] -->** Cria grupos;
- **sudo groupdel [grupo] -->** Deleta grupos;
- **sudo usermod -a -G [grupo] [usuario] -->** Colocar usuários em grupos;

**Gerenciamento de permissões**

>**Permissões:** possibilidade de alterar 3 propriedades de arquivos e diretórios(Leitura (R), Escrita (W), Execução (X))

- **1 222 333 444**<br>
 - 1: diretório ou arquivo;<br>
 - 222: Permissões do owner;<br>
 - 333: Permissões do grupo;<br>
 - 444: Permissões dos demais usuários;<br>
>*Ex: d rwx rwx rwx (tudo junto)*<br> 

- **Comando para alterar permissões:** 
- *chmod xxx file/dir*, onde 'x' representa as permissões **numéricas** (owner, groups, others);
- *chmod args file/dir*, onde 'args' pode ser representado por **+** (adiciona permissão), **-** (remove permissão) e **=** (determina as permissões, substituindo as anteriores);

**Gerenciamento básico de redes**
- Portas: acesso ao mesmo servidor, porém em serviços diferentes;
- TCP: Protocolo utilizado para transmissão de dados pela rede;
- UDP: Parecido com o TCP, porém se preocupa mais com velocidade do que com confiabilidade, portanto sendo menos seguro que o TCP;

**Compactar e descompactar arquivos**
- **tar -czvf compactado.tar.gz [diretório]** --> Compactando diretório dir1 para compactado.tar.gz;
- **tar -xzvf compactado.tar.gz (-C descompactar/)** --> Descompactando arquivo (com essa adição no comando é possível escolher o local de descompactação);
- **zip -r compacto.zip dir6** --> Compactando arquivo para *ZIP*;
- **unzip compacto.zip -d [Destino]** --> Descompactando arquivo *ZIP*; 

**[Mais informações sobre Linux](Sprint-1/README.md#curso-linux)**

##### Certificado do Curso: Linux
![Certificado Linux](Sprint-1/certificados/curso-linux.jpg)

# *SPRINT 2* | Resumo

### **Curso SQL para Análise de Dados**
![Logo SQL](/img/sql-icon.jpg)

**Comandos Básicos**

- **SELECT**: Serve para selecionar colunas de tabelas;<br>
  *Ex: select [coluna_1], [coluna_2] from [schema].[tabela] (utilizando '*' após o select seleciona todas as colunas da tabela)*

- **DISTINCT**: Serve para remover as linhas duplicadas e mostrar somente as linhas distintas;<br>
  *Ex: select ***distinct*** [coluna_1], [coluna_2] from [schema].[tabela]*

- **WHERE**: Serve para filtrar linhas de acordo com uma condição;<br>
  *Ex: select [coluna_1], [coluna_2] from [schema].[tabela] **where** condição_x=true*

- **ORDER BY**: Serve para ordenar a seleção de acordo com uma regra definida pelo usuário;<br>
  *Ex: select [coluna_1], [coluna_2] from [schema].[tabela] where condição_x=true **order by** [coluna_1] (desc após coluna_1 ordena em ordem decrescente)*

- **LIMIT**: Serve para limitar o nº de linhas da consulta;<br>
  *Ex: select [coluna_1], [coluna_2] from [schema].[tabela] **limit** [n°]*

**Operadores**
>Servem para executar operações matemáticas.

- **Aritméticos**: '+' | '-' | '*' | '/' | '^' | '%';<br>
--> '||' --> não é um operador aritmético

- **Comparação**: = | > | < | >= | <= | <>;

- **Lógicos**: AND | OR | NOT | BETWEEN | IN | LIKE | ILIKE | IS NULL

**Funções Agregadas**
>Servem para executar operações aritmética nos registros de uma coluna.

- **Tipos:** COUNT() | SUM() | MIN() | MAX() | AVG()

- **Função GROUP BY**: Serve para agrupar registros semelhantes de uma coluna;

- **Função HAVING**: Serve para filtrar linhas da seleção por uma coluna **agrupada**;

**JOIN**
>Servem para combinar colunas de uma ou mais tabelas.

- **Tipos:** Left Join, Inner Join, Right Join e Full Join.
  - **Left Join** (mais utilizado): Pegará todos os dados da tabela á esquerda e somente os dados da tabela á direita que combinarem com os da esquerda;

**UNION**
>Serve para colar uma tabela sobre a outra, desde que possuem o mesmo tanto de colunas, e as colunas possuam o mesmo tipo de unidade.

**SUBQUERIES**
>Servem para consultar dados de outras consultas.

- **Tipos:**
  - Subquery no WHERE | Subquery com WITH | Subquery no FROM | Subquery no SELECT

**Tratamento de dados**
- **Conversão de unidade:**
  - Tipos: Operador '::' | CAST

- **Tratamento geral**:
  - Tipos: **CASE WHEN:** *utilizado para criar respostas específicas para diferentes condições* | **COALESCE():** *utilizado para preencher campos nulos com o primeiro valor não nulo de uma sequência de valores.*

- **Tratamento de texto**:
  - Tipos: 
    - LOWER(): utilizado para transformar todo texto em letras minúsculas;
    - UPPER(): é utilizado para transformar todo texto em letras maiúsculas;
    - TRIM(): utilizado para remover os espaços das extremidades de um texto;
    - REPLACE(): utilizado para substituir uma string por outra string;

- **Tratamento de datas**:
  - Tipos: 
    - INTERVAL: utilizado para somar datas na unidade desejada;
    - DATE_TRUNC: utilizado para truncar uma data no início do período;
    - EXTRACT: utilizado para extrair unidades de uma data/timestamp;

- **FUNÇÕES**:
  >Servem para criar comandos personalizados de scripts usados recorrentemente.<br>

##### Certificado do Curso: SQL para Análise de Dados
![Certificado SQL para Análise de Dados](Sprint-2/certificados/Curso_SQL.jpg)

### **Curso Big Data Fundamentos 3.0**
![Img Big Data](/img/big-data-img.jpg)

- **Big Data**: coleção de conjunto de dados, grandes e complexos, que não podem ser processados por banco de dados ou aplicações de processamento  tradicionais; 

> *4 V's do Big Data*: Volume, velocidade, variedade e veracidade dos dados;<br>

- Extrair, armazenar, processar e analisar os dados a fim de gerar valor a empresa;

- **Armazenamento de Big Data:** 
  - Se os dados são estruturados ou podem ser estruturados antes do armazenamento utiliza-se um *Data Warehouse*;
  - Se os dados **NÃO** são estruturados ou **NÃO** podem ser estruturados antes do armazenamento utiliza-se um *Data Lake ou Data Store*;

- **Data Warehouse**: sistema de armazenamento que conecta e harmoniza grandes quantidades de dados de muitas fontes diferentes;
- **Data Lake**: repositório centralizado que permite armazenar todos os dados estruturados e não estruturados em qualquer escala. Os dados podem ser armazenados como estão na fonte, sem ter que primeiro estruturá-los ou filtra-los;
- **Data Store**: é um repositório para armazenar e gerenciar de forma persistente coleções de dados que incluem não apenas dados estruturados, mas também tipos de armazenamento variados;
- **Cluster**: é um conjunto de servidores com um mesmo propósito visando fornecer um tipo de serviço. Se quisermos aumentar a capacidade computacional incluímos mais máquinas no cluster;
- **Armazenamento paralelo**: consiste em distribuir o armazenamento de dados através de diversos servidores, o que permite aumentar de forma considerável a capacidade de armazenamento usando hardware de baixo custo.
- **Processamento paralelo**: objetivo de dividir uma tarefa em várias sub-tarefas e executá-laas em paralelo.
- **Cloud Computing**: é a entrega de serviços de computação pela internet ("a nuvem") para oferecer recursos flexíveis, inovação e economia de escala;
- **Machine Learning(ML)**: se concentra no uso de dados e algoritmos para imitar a forma como os humanos aprendem, melhorando gradativamente sua precisão;
- **DevOps**: se concentra na implantação contínua de software, aproveitando os recursos de TI sob demanda e automatizando a integração, o teste e a implantação de código;
- **Small Data**: Dados que estão disponíveis em quantidade mínima o suficiente para compreensão humana;
- **Dados como Serviço (DaaS)**: estratégia de gerenciamento de dados que visa alavancar os dados como um ativo de negócios para maior agilidade no processo de análise. Projetado para simplificar o acesso aos dados, oferecendo conjuntos de dados já tratados ou fluxo de dados para serem consumidos em uma variedade de formatos;

##### Certificado do Curso: Big Data Fundamentos 3.0
![Certificado Big Data Fundamentos 3.0](Sprint-2/certificados/Curso_BigData.png)

# *SPRINT 3* | Resumo

## **Curso Python 3 - Curso Completo do Básico ao Avançado** 
![Logo Python](img/python-icon.png)

- **Tipos Básicos**

    ```python
    print(True) #Booleano
    print(False) #Booleano
    print(1.2 + 1) 
    print('Tipo string')
    print('Você é ' + 3 * 'muito ' + 'legal') #Concatenação de textos. O '3' multiplicando 'muito' significa o tanto de vezes que a palavra será apresentada.
    print([1, 2, 3]) #Lista
    print({'nome': 'Pedro', 'idade': 22}) #Dicionário
    print(None)
    ```

- **Variáveis**
    ```python
    a = 10
    b = 5.2
    print(a + b) #15.2
    #As variáveis são dinâmicas.
    a = 'Agora é uma string' #Mudança do tipo da variável
    ```
- **Operadores aritméticos**
    ```python
    print(2 + 3) 
    print(5 - 3)
    print(2 * 3.6)
    print(9.4 / 3)
    print(9.4 // 3) #Resultado em valor inteiro
    print(2 ** 8) #Exponenciação
    print(10 % 3) #Resto da divisão
    ```
- **Operadores relacionais**
    ```python
    3 > 4 #False
    4 >= 3 #True
    1 < 2 #True
    3 <= 1 #False
    3 != 2 #True
    3 == 3 #True
    2 == '2' #False
    ```

- **Operadores de Atribuição**
    ```python
    a = 3
    a = a + 7
    a += 5 #Acrescentando valor de A (a=a+5)
    a -= 3 #Subtraindo valor de A
    a *= 2 #Multiplicando valor de A
    a /= 4 #Dividindo valor de A
    a %= 4 #Modulando valor de A
    a **= 8 #Exponenciando valor de A
    a //= 256 #Dividindo valor de A com resultado inteiro
    ```

- **Operadores Lógicos**
    ```python
    True or False #True
    7 != 3 and 2 > 3 #False
    not True #False
    ```

- **Operadores Unários**
    ```python
    ++a #Altera o sinal de A
    -a #Altera o sinal de A
    not 0
    ```

- **Operadores Ternários**
    ```python
    esta_chovendo = True
    'Hoje estou com as roupas ' + ('secas.', 'molhadas.' [esta_chovendo]) #Caso True a resposta será 'molhadas.' caso False 'secas.'
    ```

- **Mais Operadores**
    ```python
    #Operador de Membro
    lista = [1, 2, 3, 'Ana', 'Carla']
    2 in lista
    'Ana' not in lista

    #Operador de identidade
    x = 3
    y = x
    z = 3
    x is y #True
    y is not z #False
    #Listas também podem ter identidades comparadas
    ```

- **Conversão de Tipos**
    ```python
    a = 2
    b = '3'
    print(a + int(b))
    print(str(a) + b)
    ```    

- **Tipos Númericos**
    ```python
    a = 5
    b = 2.5
    a / b 
    a + b
    a * b
    b.is_integer() #False
    5.0.is_integer() #True
    abs(-2) #Retorna valor absoluto (2)

    #1.1 + 2.2
    from decimal import Decimal, getcontext
    Decimal(1) / Decimal (2)

    getcontext().prec = 4 #Precisão de 4 casa decimais
    Decimal.max(Decimal(1), Decimal (2)) #Retorna o maior valor
    ```

- **Tipo String**
    ```python
    "Dias D'Avila" == 'Dias D\'Avila' #Formas de utilizar aspas simples no meio da string
    texto = 'Texto entre apostrófos pode ter "aspas"'
    doc = """Texto com múltiplas 
    ... linhas"""
    #\t = TAB

    nome = 'Saulo Pedro'
    nome[0] #Acessando letra na posição 0
    nome[-3] #Acessando posição da direita para esquerda
    nome[4:] #Acessando da posição 4 em diante
    nome[:3] #Acessando do início até posição 3
    nome[2:5] #Inicia posição 2 e vai até posição 5
    nome[::2] #Pulando de 2 em 2 as posições
    nome[1::2] #Pulando de 2 em 2 as posições, iniciando na posição 1
    nome[::-1] #Apresentando string invertida
    len(frase) #Tamanho da string
    frase.lower() #Toda string em letra minúsculas
    frase.upper() #Toda string em letra maiúsculas
    frase.split() #Quebra a frase nos espaços em branco
    ```
    
- **Listas**
    ```python
    lista = [1, 5, 'Ana', 'Joao', 3.1415]
    lista.append(1) #Adicionando elemento à lista
    lista.remove(5) #Removendo elemento da lista
    lista.reverse() #Reverter a lista

    lista.index('Joao') #Mostra o índice do elemento
    lista[2] #Acessando o índice 2
    del lista[2] #Deletando elemento da lista
    ```

- **Tuplas**
    ```python
    #Diferente da lista, a tupla não pode ser modificada
    tupla = tuple() #Criando tupla
    tupla = () #Criando tupla
    tupla = ('um',) #Adicionando elemento
    tupla[0] #Visitando índice
    cores = ('verde', 'amarelo', 'azul', 'branco' )
    cores.count('azul') #Quantidade de elementos 'azul' que a tupla possui
    ```

- **Dicionários**
    ```python
    pessoa = {'nome': 'Ana', 'idade': 38, 'cursos': ['Inglês', 'Português']}
    pessoa['nome'] #Apresenta o valor da chave
    pessoa.keys() #Chaves do dicionário
    pessoas.values() #Valores do dicionário
    pessoa.items() #Chaves e valores do dicionário
    pessoa.get('idade') #Retorna o valor de 'idade'
    ```

- **Conjuntos**
    ```python
    #Não aceita elementos repetidos, não é indexada e não garante a ordenação
    a = {1, 2 , 3}
    a = set('cod3r')
    {1, 2, 3} == {3, 2, 1, 3} #True, pois contém os mesmos elementos nos 2 conjuntos
    c1 = {1, 2}
    c2 = {2, 3}
    c1.union(c2) #Cria um 3° conjunto com a união de c1 e c2
    c1.intersection(c2) #Cria um 3° conjunto com a intersecção de c1 e c2
    c1.update(c2) #Realiza a união de c1 e c2 dentro de c1
    c2 <= c1 #Verificando se é subconjunto
    c1 - c2 #Diferença entre os conjuntos
    ```

- **Interpolação**
    ```python
    nome, idade = 'Ana', 30
    print('Nome: %s Idade: %d' % (nome, idade)) #Versão mais antiga

    print('Nome: {0} Idade: {1}'.format(nome, idade)) #python < 3.6

    print(f'Nome: {nome} Idade: {idade}') #python >= 3.6
    ```

- **Estruturas de Controle**
    ```python
    #Exemplo IF-ELSE
    if 0 <= idade < 18:
        return "Menor de idade"
    else:
        return "Maior de idade"

    #Exemplo FOR
    for i in range(1, 11):
    print('i = {}'.format(i))

    #Exemplo MATCH-CASE
    match dia:
        case 2 | 3 | 4 | 5 | 6:
            return "Dia de semana"
        case 1 | 7:
            return "Fim de semana"
        case _:
            return "** inválido **"

    #Exemplo WHILE
    while numero_informado != numero_secreto:
        numero_informado = int(input('Informe o número: '))
    ```

- **List Comprehension**
    ```python
    #Exemplos
    dobros = [i * 2 for i in range(10)]
        print(dobros)

    dobros_dos_pares = [i * 2 for i in range(10) if i % 2 == 0]
        print(dobros_dos_pares)    
    ```

- **Funções**
    - Sequência de passos que recebe um conjunto de passos e retorna uma sáida.<br>

    - 2 tipos de parâmetros: posicional e nomeado;<br>
        - Posicional: parâmetros que já se espera, seguindo a mesma ordem passada na função.<br>
        - Nominal: Quando chamar a função mudar a ordem pelo nome dos parâmetros da função.<br><br>
  
    *args: vai gerar uma tupla;<br>
    **kwargs: vai gerar um dicionário;

    ```python
    #Exemplo de parâmetro com valor padrão
    def tag_bloco(texto, classe='success'):
        return f'<div class="{classe}">{texto}</div>'

    #Exemplo da chamada de função com parâmetros nomeados
    print(tag_bloco(inline=True, texto='inline'))

    # Exemplo packing
    print(soma_n(1))
    print(soma_n(1, 1))
    print(soma_n(1, 1, 1, 1, 1, 1, 1))

    # Exemplo unpacking
    tupla_nums = (1, 2, 3)
    print(soma_3(*tupla_nums))
    ```

- **Pacotes**
    ```python
    # Criação de pacote
    print(f"importado módulo {__name__} do pacote {__package__}")
    def soma(x, y):
        return x + y

    # Importação do pacote
    from pacote1 import modulo1
    print(type(modulo1))
    print(modulo1.soma(2, 3))

    # Importação direta das funções
    from pacote1.modulo1 import soma
    from pacote2.modulo1 import subtracao as sub

    print('Soma', soma(3, 2))
    print('Subtração', sub(3, 2))
    ```

- **Programação Orientada a Objetos**
    - Um objeto é composto por outros objetos;
    - Objeto é composto por atributos(dados) e comportamentos(métodos);
    -  Classe: molde --> Objeto: instância de uma classe;
    - Pilares da O.O: Herança | Polimorfismo | Encapsulamento | Abstração
    ```python
    class Data:
    def __init__(self, dia=1, mes=1, ano=1970):
        self.dia = dia
        self.mes = mes
        self.ano = ano

    def __str__(self):
        return f'{self.dia}/{self.mes}/{self.ano}'


    d1 = Data(5, 12, 2019)
    print(d1)
    ```
##### Conclusão da Sprint 3
![Conclusão da Sprint](Sprint-3/certificados/conclusão-sprint3.png)<br>
![Certificado AWS 3/10](Sprint-3/certificados/certificado-aws3_10.jpg)
<br>

# *SPRINT 4* | Resumo

## **Curso Python 3 - Seção: Programação funcional** 
![Logo Python](img/python-icon.png)
```python
#Exemplo closure
def multiplicar(x):
    def calcular(y):
        return x * y
    return calcular

#Exemplo map
lista1 = [1, 2, 3]
dobro = map(lambda x: x * 2, lista1)
print(list(dobro))

#Exemplo filter
pessoas = [
    {'nome': 'Pedro', 'idade': 11},
    {'nome': 'Mariana', 'idade': 18},
    {'nome': 'Arthur', 'idade': 26},
]
menores = filter(lambda p: p['idade'] < 18, pessoas)
print(list(menores))

#Exemplo reduce
pessoas = [
    {'nome': 'Pedro', 'idade': 11},
    {'nome': 'Mariana', 'idade': 18},
    {'nome': 'Arthur', 'idade': 26},
]

so_idades = map(lambda p: p['idade'], pessoas)
menores = filter(lambda idade: idade < 18, so_idades)
soma_idades = reduce(lambda idades, idade: idades + idade, menores, 0)
print(soma_idades)
```
## **Curso Docker para desenvolvedores** 
![Logo Docker](img/docker-icon.png)

>- **Containers** são um pacote de código que pode executar uma ação, por exemplo: rodar uma aplicação Node.js, PHP, Python, ...
>- **Imagem** é o "projeto" que será executado pelo container, todas as instruções estarão declaradas nela;<br>
***Container** é o **Docker** rodando alguma **imagem**, consequentemente
executando algum código proposto por ela;*


- **docker ps**: Mostra todos os containers que estão rodando (com a flag -a mostra todos os que já rodaram também);

- **docker run ubuntu**: Roda a imagem, no caso do ubuntu (pode ser necessária a instalação da imagem)

- **flag -it**: rodar um container e deixá-lo executando no terminal;

- **Container X VM**: Container é uma aplicação que serve para um determinado fim, não
possui sistema operacional, seu tamanho é de alguns mbs;<br>
VM possui sistema operacional próprio, tamanho de gbs, pode executar
diversas funções ao mesmo tempo;

- **flag -d**: executar container em background;

- **flag -p**: expor portas;

- **docker stop < id ou nome >**: Parar o container. Desta maneira estaremos liberando recursos que estão sendo gastos pelo
mesmo;

- **docker start < id >**: Roda um container já criado;

- **flag --name**:  Definir um nome do container;

- **docker logs < id >**: Verificar o que aconteceu em um container com o comando
logs;

- **docker rm < id >**: Remover um container da máquina que estamos executando o Docker (se o container estiver rodando ainda, podemos utilizar a flag -f (force));

- **Imagens**: Imagens são originadas de arquivos que programamos para que o Docker crie uma estrutura que execute determinadas ações em containers;

- **docker build < diretório da imagem >**: Realizar o build da imagem;

- **flag --help**: Podemos ver todas as opções disponíveis
nos comandos;

- **docker rmi < imagem >**: Remover imagens (Imagens que estão sendo utilizadas por um container, apresentarão um erro no terminal. Podemos utilizar a **flag -f** para forçar a remoção);

- **docker system prune**: Remover imagens, containers e networks não utilizados;

- **flag --rm**: Um container pode ser automaticamente deletado após sua utilização (docker run --rm < container >);

- **docker cp**: Pode ser utilizado para copiar um arquivo de um diretório para um container, ou de um container para um diretório determinado;

- **Volumes**: Uma forma prática de persistir dados em aplicações e não depender de containers para isso;

- **Tipos de volumes**: 
    - **Anônimos (anonymous):** Diretórios criados pela flag -v, porém com um nome aleatório;<br>
    Podemos criar um **volume anônimo (anonymous)** da seguinte maneira: **docker run -v /data**

    - **Nomeados (named):** São volumes com nomes, podemos nos referir a estes facilmente e saber para que são utilizados no nosso ambiente;<br>
    Podemos criar um **volume nomeado (named)** da seguinte maneira: **docker run -v nomedovolume:/data**

    - **Bind mounts:** Uma forma de salvar dados na nossa máquina, sem o gerenciamento do Docker, informamos um diretório para este fim;<br>
    O comando para criar um **bind mount** é: **docker run /dir/data:/data**

    - **docker volume create < nome >**: Criar volumes manualmente. Desta maneira temos um named volume criado, podemos atrelar a algum container na execução do mesmo;
    - **docker volume ls**: Listar todos os volumes;
    - **docker volume inspect nome**: Verificar os detalhes de um volume em específico
    - **docker volume rm < nome >**: Remover um volume existente;
    - **docker volume prune**: remover todos os volumes que não estão sendo utilizados;

- **YAML**: Uma linguagem de serialização. Usada geralmente para arquivos de configuração, inclusive do Docker, para configurar o Docker Compose;

- **Docker Compose**: O Docker Compose é uma ferramenta para rodar múltiplos containers; Teremos apenas um arquivo de configuração, que orquestra totalmente
esta situação;
    - *version*: versão do Compose;<br>
    - *services*: Containers/serviços que vão rodar nessa aplicação;<br>
    - *volumes*: Possível adição de volumes;

>   - **Comandos:**<br>
        - **docker compose up**: Isso fará com que as instruções no arquivo sejam executadas; <br>
        - **flag -d**: Compose em background; <br>
        - **docker compose down**: parar o compose; <br>
        - **docker-compose ps**: resumo dos serviços que sobem ao rodar o compose;

- **Docker Swarm**:
>Orquestração é o ato de conseguir gerenciar e escalar os containers da nossa aplicação;

- **Conceitos fundamentais**:
    - **Nodes**: é uma instância (máquina) que participa do Swarm; 
    - **Manager Node**: Node que gerencia os demais 
    - **Nodes Worker Node**: Nodes que trabalham em função do Manager; 
    - **Service**: Um conjunto de Tasks que o Manager Node manda o Work Node executar;
    - **Task**: comandos que são executados nos Nodes;

>   - **Comandos:**<br>
        - **docker swarm init**: iniciar o Swarm; <br>
        - **docker node ls**: verificar quais node estão ativos; <br>
        - **docker swarm join --token < TOKEN > < IP >:< PORTA >**: *adicionar* um novo serviço;<br>
        - **docker service create --name < nome > < imagem >**: *iniciar* um novo serviço; <br>
        - **docker service ls**: listar os serviços rodando;
        - **docker service rm <nome>**: remover serviço;<br>
        -  **docker service create --name < NOME > --replicas < NUMERO > <IMAGEM>**: criar um serviço com um número maior de réplicas; <br>
        - **docker swarm leave**: parar de executar o Swarm em uma determinada instância; <br> 
        - **docker node rm <ID>**: remover um node;<br>
        - **docker stack deploy -c < ARQUIVO.YAML > < NOME >**: rodar Compose com Swarm;<br>
        - **docker service scale < NOME >=< REPLICAS >**: criar novas réplicas nos Worker Nodes;<br>

- **Kubernetes**: 
> Uma ferramenta de orquestração de containers

- **Conceitos fundamentais:**
    - **Control Plane:** Onde é gerenciado o controle dos processos dos Nodes;
    - **Nodes:** Máquinas que são gerenciadas pelo Control Plane;
    - **Deployment:** A execução de uma imagem/projeto em um Pod;
    - **Pod**: um ou mais containers que estão em um Node;
    - **Services**: Serviços que expõe os Pods ao mundo externo;
    - **kubectl**: Cliente de linha de comando para o Kubernetes;

> - **Comandos**:<br>
    - **minikube start --driver=< DRIVER >**: inicializar o minikube;<br>
    - **minikube dashboard**: acesso ao dashboard;<br>
    - **kubectl create deployment < NOME > --image=< IMAGEM >**: criação de deployment;<br>
    - **kubectl get deployments**: verificar o Deployment;<br>
    - **kubectl get pods**: verificar os Pods<br>
    - **kubectl config view**: verificar como o kubernetes está configurado;<br>
    - **kubectl expose deployment < NOME > --type=< TIPO > --port=< PORT >**: criar um serviço e expor nossos Pods;<br>
    - **minikube service < NOME >**: acessar nosso serviço;<br>
    - **kubectl get services**: obter detalhes dos Services já criados;<br>
    - **kubectl scale deployment/< NOME > --replicas=< NUMERO >**: replicando a aplicação;<br>
    - **kubectl get rs**: chechar réplicas;<br>
    - **kubectl scale deployment/< NOME > --replicas=< NUMERO_MENOR >**: reduzir o número de Pods;<br>
    - **kubectl set image deployment/<NOME> < NOME_CONTAINER >=< NOVA_IMAGEM >**: atualizar a imagem;<br>
    - **kubectl rollout status deployment/< NOME >**: verificar uma alteração;<br>
    - **kubectl rollout undo deployment/< NOME >**: voltar a alteração;<br>
    - **kubectl delete service < NOME >**: deletar um serviço do kubernetes;<br>
    - **kubectl delete deploymnet < NOME >**: deletar um Deployment do Kubernetes;<br>
    - **kubectl apply -f < ARQUIVO >**: executar arquivo de deployment;<br>
    - **kubectl delete -f < ARQUIVO >**: Para parar de executar este deployment baseado em arquivo, o declarativo, utilizamos também o delete. Desta maneira teremos os Pods sendo excluídos e o serviço finalizado;<br>

## **Estatística Descritiva com Python** 
![Logo Python](img/python-icon.png)
- **Gráficos de barras/colunas**
```python
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np

#Variáveis para os gráficos devem ser declaradas antes, nas anotações só estarão presentes as funções para os gráficos.

#Barras horizontais
plt.barh(x2, y, color='g')
plt.xlabel('Variável eixo X', size=18)
plt.ylabel('Categorias', size=16)
plt.title('Titulo do meu gráfico')

#Barras verticais
plt.bar(x, y, color='r')

sns.barplot(x=x, y=y) #Outro exemplo

#Gráfico de setores
plt.pie(y, labels=x, radius = 1.25)
plt.show()

#Gráfico de linhas 
plt.plot(x1, y, 'o-y')
plt.xlabel('Eixo X', size=12)
plt.ylabel('Eixo Y', size=12)
plt.title('Titulo do gráfico', size=16)
plt.show()

#Histogramas
plt.hist(x, bins=50, color='b')
plt.xlabel('Eixo X')
plt.ylabel('Frequências')

```

- **Medidas de tendência central (MTC)**:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from bokeh.sampledata.iris import flowers as dados

dados.shape
dados.head(3) #Apresenta as 3 primeiras linhas da tabela

#Cálculo da média
med_sl = np.mean(dados['sepal_length'])
med_sl #Média coluna sepal_length

np.mean(dados) #Média de todas as colunas

#Calculo mediana
mediana_sl = np.median(dados['sepal_length'])
mediana_sl

#Cálculo moda
moda_sl = dados['sepal_length'].mode()
moda_sl

#Separatrizes
p10 = np.quantile(dados['sepal_length'], 0.10)
p10

#Informações condensadas
dados.describe()

#Visão espapcial das estatísticas descritivas
dados.head()

plt.scatter(x, y)
plt.xlabel('sepal_length')
plt.ylabel('sepal_width')

plt.plot(np.mean(x), np.mean(y), 'or')
plt.plot(x.median(), y.median(), 'oy')
plt.plot(x.mode(), y.mode(), 'og')
```

- **Medidas de dispersão (MD)**:
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from bokeh.sampledata.iris import flowers as dados

#Cálculo  da amplitude total
dados.max()
dados.min()
amplitude = dados.iloc[:, 0:4].max() - dados.iloc[:, 0:4].min()
amplitude

np.max(dados.iloc[:, 0:4])
np.min(dados.iloc[:, 0:4])
amplitude2 = np.max(dados.iloc[:, 0:4]) - np.min(dados.iloc[:, 0:4])

# Cálculo da Amplitude Interquartílica: dq = Q3 - Q1
np.quantile(dados['sepal_length'], 0.75)
q3 = dados['sepal_length'].quantile(0.75)
q1 = dados['sepal_length'].quantile(0.25)
dq = q3 - q1
dq

dqt = dados.quantile(0.75) - dados.quantile(0.25)
dqt

#Desvio médio absoluto
dados.mad()

#Cálculo da variância e desvio padrão
dados.var(numeric_only=True)
np.var(dados)
dados.std()
np.std(dados)

#Cálculo do coeficiente de variação - CV = S/X*100
cv = np.std(dados)/np.mean(dados)*100
cv

cv2 = dados.std()/dados.mean()*100
cv2
```

- **Medidas de assimetria**:
```python
import seaborn as sns
from bokeh.sampledata.iris import flowers as dados
import matplotlib.pyplot as plt

sns.set(style='whitegrid', color_codes=True)
sns.boxplot(data = dados)

plt.boxplot(dados['sepal_length'])
plt.show()
```
##### Conclusão da Sprint 4
![Conclusão da Sprint](Sprint-4/certificados/conclusão-sprint4.png)
![Certificado Docker](Sprint-4/certificados/curso_docker.jpg)
![Certificado Estatística com python](Sprint-4/certificados/curso_estatistica.jpg)<br>

# *SPRINT 5*
##### Conclusão da Sprint 5
![Conclusão Sprint 5](Sprint-5/certificados/aws-partner-sales-accreditation-business.png)
![Conclusão Sprint 5](Sprint-5/certificados/aws-cloud-quest-cloud-practitioner.png)
![Conclusão Sprint 5](Sprint-5/certificados/aws-partner-accreditation-technical.png)
![Conclusão Sprint 5](Sprint-5/certificados/aws-partner-cloud-economics-accreditation.png)
![Conclusão Sprint 5](Sprint-5/certificados/Exam-Prep-AWS-Certified-Cloud-Practitioner.png) *Badge ainda não disponível

# *SPRINT 6*

### **[Evidências da Sprint 6 - Clique aqui](Sprint-6/README.md)**

##### Conclusão da Sprint 6
![Certificado conclusão](Sprint-6/certificados/UC-8085776c-abe9-4844-9135-e43a3634c5f1.jpg)
![Certificado conclusão](Sprint-6/certificados/Data%20Analytics%20Fundamentals%20(Portuguese).png)
![Certificado conclusão](Sprint-6/certificados/Data%20Analytics%20on%20AWS%20(Business)%20(Portuguese).png)
![Certificado conclusão](Sprint-6/certificados/Introduction%20to%20Amazon%20Kinesis%20Streams.png)
![Certificado conclusão](Sprint-6/certificados/Introduction%20to%20Amazon%20Kinesis%20Analytics.png)
![Certificado conclusão](Sprint-6/certificados/Introduction%20to%20Amazon%20Elastic%20MapReduce%20(EMR)%20(Portuguese).png)
![Certificado conclusão](Sprint-6/certificados/Introduction%20to%20Amazon%20Athena%20(Portuguese).png)
![Certificado conclusão](Sprint-6/certificados/Introduction%20to%20Amazon%20Quicksight%20(Portuguese).png)
![Certificado conclusão](Sprint-6/certificados/Introduction%20to%20Amazon%20Athena%20(Portuguese).png)
![Certificado conclusão](Sprint-6/certificados/Getting%20Started%20with%20Amazon%20Redshift.png)
![Certificado conclusão](Sprint-6/certificados/Deep%20Dive%20into%20Concepts%20and%20Tools%20for%20Analyzing%20Streaming%20Data%20(Portuguese).png)
![Certificado conclusão](Sprint-6/certificados/Best%20Practices%20for%20Data%20Warehousing%20with%20Amazon%20Redshift%20(Portuguese).png)
![Certificado conclusão](Sprint-6/certificados/Serverless%20Analytics%20(Portuguese).png)

---
## Cursos Complementares | *Link para resumos*

#### **[Métodos ágeis de A a Z](/Cursos-Complementares/metodos-ageis.md)** <br>
#### **[Segurança em Aplicações WEB](/Cursos-Complementares/seguranca-web.md)**

---
**[Voltar ao topo](#pb-compass-uol)**