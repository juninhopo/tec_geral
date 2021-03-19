# Utilizacoes e Aplicacoes do Java

- Desenvolvimento de aplicativos corporativos de grande porte.

- Desenvolvimento de aplicativos Web

- Fornecimento de aplicativos para dispositivos voltados para o consumo popular (celulares, pagers, PDAs etc)

- Entre isso existem muitos outros propositos

# Como e o funcionamento do java?

Editor - .java - Compilador - .class - Carregador - bytecodes - Verificador - bytecodes - Interpretador

### Editor - E o local onde realiza a escrita (desenvolvimento) do programa (codigo fonte). Se faz necessario um editor de texto como o bloco de notas do Windows ou Vi do Linux (respeita meu VSCODE). Existem tambem os ambientes de desenvolvimento integrado (IDE = Integrated Development Enviroment) que fornecem muitas ferramentas de suporte ao processo de desenvolvimento de software em Java e outras linguagens.

- NetBeans
- Eclipse
- JCreator
- BlueJ

### Verificador - Enquanto as classes sao carregadas, o verificador de bytecode examina os codigos para assegurar que eles sao validos e nao violam restricoes de seguranca do Java. O Java impoe uma forte seguranca para certificar-se de que os programas em Java que chegam pela rede nao danifiquem arquivos do Sistema.

### Interpretador - Execucao - A JVM executa o programa interpretando o bytecodes gerado na fase de compilacao. Com isso, sequencias de acoes especificadas pelo programados sao, enfim, executadas. Atualmente, as JVM utilizam uma combinacao de Interpretacao e de compilacao just-in-time (JIT). Nesse processo, a JVM analise os bytecodes a medida que eles sao interpretados. Procurando hot spots (pontos ativos) - parte dos bytecodes, que sao executadas com frequencia. Para essas partes, um compilador JIT, conhecido como compilador Java HotSpot, traduz os bytecodes para a linguagem de maquina do computador subjacente.

### Carregador - Todo programa deve ser colocado na memoria antes de poder executar. O carregador de classe transfere os arquivos .class contendo os bytecodes do programa para a memoria principal. O carregador de classe tambem carrega qualquer arquivo .class fornecido pelo Java que seu programa utiliza. Os arquivos .class podem ser carregador a partir de um disco em seu sistema ou em uma rede.

### Compilador - O compilador Java converte o codigo-fonte Java em bytecodes, que representam as tarefas a serem realizadas durante a fase de execucao. Os bytecodes sao executados pela Java Virtual Machine (JVM) - uma parte do JDK e a base da plataforma Java. A maquina virtual Java (VM - Virtual Machine) e um aplicativo de software que simula um computador, mas oculta o sitemas operacional e o hardware subjacentes dos programas que interagem com a VM.

# Como voce por ter um Ambiente de Programacao em Java?

O ambiente de desenvolvimento de software em Java, Java SDK (antigamente JDK), e formado, essencialmente, por um conjunto de aplicativos que permite, entre outras tarefas, realizar a compilacao e a execucao de programas escritos na linguagem Java. Este ambiente pode ser baixado gratuitamente a partir do site da Sun Microsystems http://java.sun.com

As ferramentas basicas do kit de desenvolvimento Java sao:

- O compilador Java, javac
- O interpretador de aplicacoes Java (maquina virtual), java
- O interpretador de applets Java, appletviewer

# As convencoes do java

A linguagens de programacao Java e "Case sensitive". Existem varias convensoes utilizadas, sao elas:

- Nomes de variaveis e metodos comecam com letras minusculas

- Nomes de classes iniciam com letras maiusculas

- Nomes compostos: utilizar letras maiusculas para as iniciais das palavras.

- Letras maiusculas para as constantes

Case sensitivity - Sensivel ao tamanho: em computacao significa que um programa ou um compilador faz a diferenciacao entre letras maiusculas e minusculas, ou seja,  Maiuscula e diferente de maiuscula. O sistema operacional linux e case sensitive bem como as linguagens C, Java, C Sharp entre outras.

# Comentarios em Java

Existem tres formas de se inserir comentarios:

// Comentarios em uma linha

/* Comentario em uma ou mais linhas */

/** Documento comentarios */

Quando o comentario tipo 3 e colocado imediatamente acima da declaracao (de uma funcao ou variavel), indica que o comentario podera ser incluido automaticamente em uma pagina HTML (gerado pelo comando javadoc - gerador de documentacao do JAVA).

# Tipos de Dados em Java

O java e uma linguagem de programacao fortemente tipada, ou melhor, necessita que todas as variaveis tenham um tipo declarado. Existem 8 tipos primitivos. Seis deles sao numericos, um e o caractere e o ultimo e o booleano.

 - int
 - short
 - byte
 - long
 - float
 - double
 - char
 - boolean

# Declarando e Atribuindo Valores a Variaveis

A declaracao de variaveis em Java exige que o tipo da variavel seja declarado. Voce inicia a declaracao.