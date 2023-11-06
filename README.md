# # Python
## ## Indice

<a href="#Contexto"># Contexto </a>
<br>
<a href="#-Linguagens-Usadas"># Linguagens Usadas </a>
<br>
<a href="#-Comandos"># Comandos </a>
<br>
<a href="#Aula-1">#  Aula 1 </a>
<br>
<a href="#Aula-2">#  Aula 2 </a>
<br>
<a href="#Aula-3">#  Aula 3 </a>
<br>
<a href="#Aula-4">#  Aula 4 </a>
<br>
<a href="#Aula-5">#  Aula 5 </a>
<br>
<a href="#Aula-6">#  Aula 6 </a>
<br>
<a href="#Aula-7">#  Aula 7 </a>
<br>
<a href="#Aula-8">#  Aula 8 </a>
<br>
<a href="#Aula-9">#  Aula 9 </a>
<br>
<a href="#Aula-10">#  Aula 10 </a>
<br>
<a href="#Aula-11">#  Aula 11 </a>
<br>
<a href="#Aula-12">#  Aula 12 </a>
<br>
<a href="#Obs">#  Observações </a>
<br>
<a href="#-Autor"> # Autor </a>
<br>

<hr>
<hr>

## Contexto:

  * Esse README foi criado com o propósito se reunir os comandos, ensinamentos, e dicas sobre o curso de Python da FIAP; lecionador por: Francisco Elanio Bezerra.

  * Além disso, esse README desempenha a função de centralizar, organizar e facilitar o entendimento. Além de relembrar os comando e suas funções mais facilmente.

## # Linguagens Usadas
#### 1. Python, usando o Jupyter Notebook

<hr>
<hr>

## # Comandos

1. ### Aula 1

  * <h4>Apresentação do curso</h4>

    <hr>

  * <h4> input -- </h4> É usado para soliciatar um valor do usuario, sendo o valor convertido em string(conjunto de caracteres).

    - <h5> float -- </h5> converte o valor de string para numeros decimais, podendo usa-los para fazer contas.
    
    - <h5> int -- </h5> Converte a sting para numeros inteiros, nao permitindo numeros decimais, podendo se usado para fazer conta.

     <hr>

  * <h4> if // elif // else -- </h4> É usado para se fazer ações especificas dentro do codigo.

    - <h5> if -- </h5> É usado para iniciar as condicoes, caso a variavel tenha determidado valor, ou caso a variavel se enquadra dentro da situacao determidada, ira execultar um acao especifica dentro dessa condicao
    
    - <h5> elif -- </h5> É usado da mesma forma do "if", porem so pode ter 1 "if" na estrutura, e se precisar de mais condicoes de deve usar o elif em vez de diversos "if".
    
    - <h5> else -- </h5> É usado para finalizar a estrutura condicional, caso nao tenha nenhuma situacao que se enquadra em nenhuma outa, ira execultar esse comando.     
     

<hr>
<hr>

2. ### Aula 2

  * <h4> Pseudocódigo --</h4> Conteudo Teorico.
    
    <hr>
  
  * <h4>fluxogrma -- </h4> Conteudo Teorico. <br> Usado para definir quais serao os passos minimos a ser realizado e qual ira ser a ordem. <br> Além disso, eles sao compostos por caixas e setas, a forma da caixa diz se será de açao, inicio, entrada, etc...
    
    <hr>

  * <h4> ["valor 1" ; "valor 2"] --  </h4> essa propriedade é usada para atribuir um valor a uma variavel, e esse valor é umaj lista, onde o conteudo da lista deve estar em seu interior. <br> Além disso, para se usar string, se deve colocar o valor ente aspas simples oud duplas ( "" ; '').

     <hr>

  * <h4> min -- </h4> Usado para saber qual e o menor numro dentro de uma lista ou de uma variavel.

    <hr>

  * <h4> .remove() -- </h4> Propriedade que remove algum termo da lista ou vairavel. <br> Alem disso, se deve ser usado logo em seguida da vaiavel que o valor sera removido, e no parentese () de deve colocar o valor a ser removido.
    
    <hr>

  * <h4> sum() -- </h4> propriedade que soma todos os valores de uma variavel/lista. <br> Obs: a variavel deve estar dentro do parenteses.



<hr>
<hr>

3. ### Aula 3 
  
  * <h4>print -- </h4> mostra alguma mensgem para o usuario. <br> Porém, nao esta completo, pois precisa de complemento, como a mensgem e/ou a variavel que quer mostrar. <br> Além disso, e possivel fazer contas rapidas ja mostrando o resultado para o usuario.

    - <h5>"mensagem" --<h5>  Para p</h5> oder exibir uma mensagem se deve ter as ("aspas"), pois assim sera considerado como uma string e exibira a mesnagem exata.  <br> exemplo: <br> print("mensagem") -- exibir somente a mensagem.

    - <h5> variavel -- </h5> Para exibir somente uma variavel, se deve chamar a variavel e a deixar sozinha, caso queira mais de uma, se pode colocar ( ',' ) e a outra variavel. <br> exemplos: <br> print(variavel) -- exibir somente uma variavel. <br> print(variavel_1, variavel_2) -- exibe duas variaveis de uma vez e na ordem colocada.
    
    - <h5>"mensagem", variavel -- </h5> Para poder exibir uma mensagem se deve ter as ("aspas"), pois assim sera considerado como uma string e exibira a mesnagem exata. <br> Contudo, para mostrar algum valor de variavel de usar a ( ',' ) depois da mensagem, e logo em seguida a variaval a ser mostrada. <br> exemplo:<br> print("mensagem exibida:", valor da variavel) -- para exibir mesagem e valor da variavel.
    
    - <h5>para poder fazer contas e mostrar seu valor -- </h5> Se pode fazer cantas diretamente no print, usando variaveis ou os numeros diretamente. <br> exemplos: <br> print(100 + (100 * 5 / 100)) -- ira mostrar o valor da operacao matematica, no caso ira dar: 105 <br> print(salario * (salario * aumento / salario)) -- ira fazer uma conta para saber qual e o aumento do salario, onde se define previamente as variaveis com os valores escolhido.
      
    <hr>
  
  * <h4>nomeando e definindo uma variavel -- </h4> 
        
    - pode conter letras e numero <br>
        
    - pode conter somente letras, mas nao pode ser so numeros <br>
        
    - deve ser iniciado por pelo menos uma letra ou sublinha ("_") <br> 
        
    - nao se pode iniciar por numeros <br>
        
    - nao pode ter espaco em branco, mas pode contortar usando o "_" <br>
       
    - depois que a variavel é criada deve ter o (=) para definir o valor que ela receberá.
      <hr>
  
  * <h4>operadores logicos -- </h4>

    - <h5> (==) -- </h5> usado para igualdade <br>

    - <h5> (>) -- </h5> maior que <br>

    - <h5> (<) -- </h5> menor que<br>

    - <h5> (!=) -- </h5> diferente que <br>

    - <h5> (>=) -- </h5> maior ou igual <br>

    - <h5> (<=) -- </h5> menor ou igual <br>
    <hr>
    
  * <h4> operadores de comparacao --</h5>

    - <h5> and ( && ) -- </h5> usado juntar algo; ambos precisam ser verdadeiros para ser verdadeiro. <br> Mesmo que um deles seja verdadeiro e o outro falso, ira ler como falso <br> <br>
        
    - <h5> or ( || ) --  </h5> um deles precisa ser verdadeiro para ser verdadeiro, mesmo que um seja falso ira ler como verdadeiro <br><br> 
        
    - <h5> not ( ! ) -- </h5> o verdadeiro vira falso e o falso vira verdadeiro <br>
    
    <hr>
  
  * <h4> len() --</h4> Esse comando conta quantos caracteres tem eum uma lista ou variavel, e pode ser usado em string ou numeros.

    - <h5> a [ posicao ] -- </h5> usado para saber a prosicao de uma letra em especifico, no lugar de "posicao" se coloca o numero correspondente do caractere. <br> OBS: o len comenca a contar apartir do zero ( 0 ), logo a contagem seria: 0, 1, 2, 3.
    
    <hr>
  
  * <h4> operacaos de fatiamento -- </h4> 

    - <h5> omitir caracteres a esquerda -- </h5> se utiliza a variavel que contem a string e usa o [], informando de qual letra para frente sera mostrada. <br> exemplo: <br> variavel = "Let's learn Python" <br> s[10:] <br> n Python <br>
        
      <h5> OBS: o ":" significa continue, no caso seria mostra as letra a partir do caractere 10 para frente </h5>

    - <h5> Omitir os caracteres da direita -- </h5> se utiliza a variavel que contem a string e usa o [], informando de qual letra para traz sera mostrada. <br> exemplo: <br> variavel = "Let's learn Python" <br> s[:10] <br> Let's lear <br>
        
      <h5> OBS: o ":" significa continue, no caso seria mostra as letra a partir do caractere 10 para traz </h5>
    
    - <h5> mostrar somente os ultimos caracteres -- </h5> se utiliza a variavel que contem a string e usa o [], informando de qual o numero correspondente a letra com um "-". <br> exemplo: <br> variavel = "Let's learn Python" <br> s[-2:] <br> on <br>
        
      <h5> OBS: o ":" significa continue, no caso seria mostrar somente as ultimas duas letras da string </h5>
    
    - <h5> ocultar os ultimos caracteres -- </h5> se utiliza a variavel que contem a string e usa o [], informando de qual o numero correspondente a letra com um "-". <br> exemplo: <br> variavel = "Let's learn Python" <br> s[:-2] <br> on <br>
        
      <h5> OBS: o ":" significa continue, no caso seria para ocultar somente as ultimas duas letras da string </h5>

    
    <hr>
  
  * <h4> juncao de string -- </h4>

    - juncao de variavel com string mais uma string. -- <br> exemplo: <br> variavel = "Pytho" <br> variavel + "n" <br> Python
        
    - juncao de variavel com string mais de uma string. -- <br> exemplo: <br> variavel = "Python " <br> variavel + "é " + "impressionante“ <br> Python é impressionante

    - juncao de varias variaveis com string -- <br> exemplo: <br> variave_1 = "Python " <br> variavel_2 = "é " <br> variavel_3 = "impressionante" <br> variave_1 + variavel_2 + variavel_3 <br> Python é impressionante
    
    <hr>
 
  * <h4> composicao de string</h4>

    - <h5> numeros inteiros ( %d ) -- </h5> Para poder substituir um valor inteiro na string se deve utilizar a ( %d ), e logo quando acabar a string se deve conectar ele a uma variavel, usando %(variavel, ou numero).

    - <h5> numeros com virgula ( %f ) -- </h5> Para poder substituir um valor decimal na string se deve utilizar a ( %f ), e logo quando acabar a string se deve conectar ele a uma variavel, usando %(variavel, ou numero). 

    - <h5> string (textos) ( %s ) -- </h5> Para poder substituir uma string dentro da string se deve utilizar a ( %s ), e logo quando acabar a string se deve conectar ele a uma variavel, usando %(variavel, ou numero). 

    - <h5> exemplo 1: </h5>  "%s tem %d anos e apenas R$%2f no bolso"% ("João", 22, 51.34) <br>
        João tem 22 anos e apenas R$51.34 no bolso
        
    - <h5> exemplo 2: </h5> grana= 51.34 <br> idade= 22 <br> nome = "João" <br> "%s tem %d anos e R$%f no bolso."% (nome, idade, grana) <br> João tem 22 anos e apenas R$51.34 no bolso
    <hr>

  
  * <h4> input </h4> Esse comando solicita dados do usuario, todos os valores sao convertidos para string, e deve ser jogado em uma variavel. <br> exemplo: <br> nome = input( "Digite seu nome:") <br> print(f"Você digitou {nome}").

    - <h5>int --</h5> converte o valor recebido em numero inteiro. <br> Exemplo: <br> variavel = float(input("vc tem quantos anos?"))
        
    - <h5>float -- </h5> converte o valor recebido em numero decimal. <br> Exemplo: <br> variavel = float(input("vc tem quantos centavos?"))
    
<hr>
<hr>

4. ### Aula 4 
    
  * <h4> if -- </h4> É uma estrutura de decisao que decide se quando uma parte do codigo sera ativado ou ignorada. <br> Esse comando ira iniciar a estrutura de decisao. <br> Se o if nao estiver idendato no outro, ira reconhecer como condicoes independentes e irao rodar sem necessitar da outra.

    - E possivel fazer multiplas comparacoes, usando os operdadores de comparacao (and, or, not) <br>

    - o ideal e usar somente uma vez, mas caso queira multas condicoes distintas, se deve usar o elif.

    - <h5>estrutura -- </h5>  if (condicao): identacao com o comando
    
    <hr>
  
  * <h4> elif -- </h4> Operador de condicao que pode ser usado para fazer o mesmo trabalho do if, sendo influenciado pelo if anterior, nao tem limites do quando de elif pode ser usado. <br> 
        
    - <h5>estrutura -- </h5> ela é a mesma do if; ou seja, if (condicao): identacao com o comando

    <hr>
  
  * <h4> else -- </h4> E usado para enquadrar situacoes gerais, dos quais nao fazem parte das condicoes desejadas, usado principalmente como rota de dados nao desejados ou que n servem para atender alguma condicao.

    - <h5>estrutura -- </h5> ela é diferente do if e do elif, pois nao existe condicao, sendo usadao como: else:. nessa ultima parte vc identa algo que vc queira fazer

    
    <hr>
  
  * <h4> lower() -- </h4> converte um texto para letras minusculas.
    
    <hr>
  
  * <h4> upper() --</h4> converte um texto para letras maiusculo 
    <hr>
  
  * <h4> in -- </h4> verifica se o valor esta presente em uma sequencia, pode ser um uma string ou em uma lista. <br> Porém ela esta incompleta, precisando de outros comandos para funcionar, tais como o for, if, variavel ou lista
    
    <hr>
 
  * <h4> not in -- </h4> É o contrario do in, pois ele verifica se o valor nao esta na variavel desejada.
    
    <hr>
  
  * <h4> condicao dentro de condicao --</h4> Isso acontece quando um if e dentado dentro do outro, ou seja, precisa satisfazer a primeira condicao para acessar a proxima. <br> nao a limite de condicoes sobrepostas

    <h5>Obs: </h5> todo if precisa de um else, incusive aki
      
    <hr>
    
  * <h4> for -- </h4> Esse comando percorre elementos dentro der uma lista ou uma string e realizar operancoes em cada elemento. <br> Porém, ele nao esta completo, precisando do da criacao de uma variavel, do "in", da lista e finalizando com ":". <br> Exemplo: <br> for variavel_criada in lista_pre-existente: <br> print(numero) 
        
    - <h5> continue -- </h5> Ejgssa propriedade para a acao atual do loop e ira fazer a proxima em sequencia
        
    - <h5> break --</h5> Essa propriedade para o loop sem mesmo percorrer toda a lista.
        
    - <h5> if -- </h5> Pode se usar o if dentro do for, para poder fazer alguma condicao especifica, como relatar a falta de um ingrediente.

    - <h5> for -- </h5> Caso seja feito uma identacao, ira ter uma combinacao, do elemento 1 no elemento 2
   
<hr>
<hr>


5. ### Aula 5
  
  * <h4> Operadores de atribuicao -- </h4> sao propriedades para facilitar e simplificar as operacoes matematicas nos codigos.

    - <h5> += -- </h5> soma o lado  esquerdo com o lado direito; e em seguida atribui o resulatdo ao lado esquerdo. <br> Exemplo: <br> a += b --> a = a + b. 
        
    - <h5> -= -- </h5> subtrai o lado  esquerdo com o lado direito, em seguida atribui o resulatdo ao lado esquerdo. <br> Exemplo: <br> a -= b --> a = a - b. 
        
    - <h5> *= -- </h5> multiplica o lado  esquerdo com o lado direito; em seguida atribui o resulatdo ao lado esquerdo. <br> Exemplo: <br> a *= b --> a = a * b. 
        
    - <h5> /= -- </h5> divide o lado  esquerdo com o lado direito; em seguida atribui o resulatdo ao lado esquerdo. <br> Exemplo: <br> a /= b --> a = a / b. 
        
    - <h5> %= -- </h5> divide o lado  esquerdo com o lado direito, pegando o resto da divisao, em seguida atribui o resulatdo ao lado esquerdo. <br> Exemplo: <br> a %= b --> a = a % b. 

    - <h5> OBS: </h5> Esse ultimo comando serve para encontrar o resto de alguma divisao, ex: 2 / 2 tem o resto 0; enquanto 3/2 tem o resto 1.
         
  <hr>
    
  * <h4> while -- </h4> É uma de repeticao parecida com o for, porem as suas repeticoes nao sao bem definidas, precisando de um contador. <br> Além disso, essa estrutura ira rodar um codigo ate que encontre o que deseja ou que alguma comando pare.
       
    - <h5> contador -- </h5> usado para avancar a condicao. <br> Além disso, o contador deve ser definido fora do comando while. <br> ex: <br> fim = int(input( "Digite o último número a imprimir: ")) <br> conatdor = 1 <br> while contador <= fim: <br> contador = contador + 1 <br> print(x)
 
<hr>
<hr>


6. ### Aula 6
  
  * <h4> Checkpoint/prova </h4>

      <hr>

  * <h4> reversed -- </h4> Inverte a posicao da lista, o ultimo se torna o prmeiro e assim consecutivamente, basicamente inverte a ordem da lista

  <hr>

  * <h4> :: -- </h4> pula casas dentro da lista, se deve utilizar dentro do for. <br> para poder utilizar se deve colocar o numero em que ira comecar a ler a lista e depois colocar de quantas em quantas casas ira pular. <br> Obs: os termos da lista comeca a ontar apartir do 0.  

  * <h4> %s -- </h4> comando usado para substituir um valor de string dentro do print, sendo necessario informar qual sera a variavel que ira subistituir. E para isso e usado o " %(variavel)" depois da mensagem

      <hr>
  
  * <h4> %f -- </h4> comando usado para substituir um valor quebrado do tipo float dentro do print, sendo necessario informar qual sera a variavel que ira subistituir. E para isso e usado o " %(variavel)" depois da mensagem

      <hr>
  
  * <h4> %d --</h4> comando usado para substituir um valor inteiro dentro do print, sendo necessario informar qual sera a variavel que ira subistituir. E para isso e usado o " %(variavel)" depois da mensagem

      <hr>
<hr>
<hr>

7. ### Aula 7
  
  * <h4> zip() -- </h4>Coamndo que permite somar listas. <br> Além disso, ela pode ser usada em comjunto com o for, o que permite somar os termos correspondentes entres as listas. <br> O zip pode ser usado para mais de dois termos, sendo possivel juntar termos de diferentes tipos, como numeros e string
    
    <hr>
    
  * <h4> combinacao de listas -- </h4> Para se combinar listas se deve criar uma vairavel e nessa variavel somar as listas ja existentes. <br> OBS: o resultado sera uma lista e depois a outa.
    
    <hr>
    
  * <h4> enumerate() -- </h4> Essa propriedade e usada para enumerar os termos correspondendes, podenso ser usada com outas propriedades como o zip.
    
    <hr>
    
  * <h4> .append -- </h4> permite adicionar elementos a alguma lista 
   
<hr>
<hr>

8. ### Aula 8

  * for -- <br> Percorre\le as listas, tambem pode ser usado para complementar as listas ou fazer alguma operacoes entre elas. <br> Além disso, o range somente funciona com numeros, nao podendo usar string. 

    - <h5> continue -- </h5> É uma propriedade que ira continuar a lista ate que finalize todas as conducoes. <br> Porém, toda vezes que ela repetir, ira pular o termo que ja foi contado e so parará quando nao haver mais termos que se encaxem na condicao

    <hr>

  * <h4> min -- </h4> percorre a lista e verifica qual e o menor termo

     <hr>

  * <h4> max -- </h4> Percorre a lista e verifica qual e o maior termo da lista

      <hr>
    
  * <h4> sum -- </h4> Soma todos os termos da lista.
   
    <hr>
    
  * <h4>len -- </h4> Mostra quantos termos tem dentro da lista, independente se for uma string ou numeros.
   

<hr>
<hr>

9. ### Aula 9

  * <h4> Corringindo o checkpoint 2 </h4>

      <hr>

  * <h4> upper -- </h4> Deixa todas as letras mauiusculas

      <hr>
  
  * <h4> introducao ao pandas</h4>

  * <h4>  pip install -- </h4> usado para instalar uma biblioteca, onde depois desse coamndo se deve colocar o nome da biblioteca a ser instalada

      <hr>

  * <h4> import (biblioteca) as (apedido) </h4> comando usado para chamar uma biblioteca ja instalada, logo depois a renomenado para poder ficar mais facil chama-la quando quiser

    <hr>
  * <h3> pandas </h3> biblioteca pandas: 

    * <h4> {'nome coluna' : [valor da culuna], }</h4> se deve criar uma variavel, adicionar chaves e dentro dessas chaves ira colocar a estrutura " 'nome da culuna' : [valores] ' " o dois pontos servem para dizes que os valores do parenteses esta ligado a coluna criada anteriormente. <br> OBS: para exibir as informacoes se deve usar o comando abaixo. <br> OBS 2: se deve colocar esse comando dentro de uma variavel

      <hr>

    * <h4> biblioteca/apelido.DataFrame(nome_variavel_tabela) </h4> cria um DataFrame e inicia uma tabela do frame work (da biblioteca "pandas"), colocando os dados em forma de tabela do exel. <br> OBS: para se ter os dados se usa a estrutura acima. <br> OBS 2: se deve colocar esse comando dentro de uma variavel

      <hr>
<hr>
<hr>

10. ### Aula 10

* <h3> Pandas </h3> biblioteca do pandas:

    * <h4> pd.read_csv('caminho.csv') </h4> comando usado para se ler um arquivo do exel, onde a terminacao seja "csv" <br> OBS: deve ser usado pelo pandas. <br> OBS 2: se deve colocar esse comando dentro de uma variavel
    
     <hr>

    * <h4> variavel_dados.info() </h4> esse comando le os dados da variavel e informa qual e o tipo do dado contido.

        <hr>
    
    * <h4> varaivel.iloc -- </h4> pega linha por linha dos dados, onde nao se cria uma tabela, mas sim os dados irao parecer em ordem de posicao. 

<hr>
<hr>

11. ### Aula 11

  * <h4> def nome_funcao (variavel)-- </h4> cria uma funcao, logo depois a nomeia, e define as vaiaveis a ser utilizada

      <hr>

  * <h4> return variavel -- </h4> retorna o valor da variavel, tendo que informar qual e o valor desejado.

    - <h5> OBS: para printar o resultado, deve chamar o que quer ser printado no return, e para printar se deve chamar o nome da funcao e sua variavel. <br> Basicamente colocar o que colocou em def ... sem o def</h5>


<hr>
<hr>

12. ### Aula 12

### Obs:
    
1. (&-nbsp) -- <br>
    da espaco dentro do site, para as coisas ficarem mais afastado.<br> obs: é tudo junto, nao tendo espaco ou traço.  
        
    <hr>

2. ctrl + home + end -- <br> Seleciona uma linha.
    
    <hr>

3. shift + ( ; ) -- <br> Comenta uma linha ou palavra 

    <hr>

4. hr -- <br> 
    Esse comando cria uma linha de divisoria

    <br>

5. truplas -- <br> 
    É uma sequancia de valores de qualquer tipo ou forma

    <br>

<hr>
<hr>

### # Autor
1. Gustavo Bezerra Assumção
        
  * estudande da FIAP
       
  * <a href="https://www.linkedin.com/in/gustavo-bezerra-829202289/"> linkedin </a>
        
  * <a href="https://www.instagram.com/gustavo_b017/"> Instagram </a>
    
  * <a href="https://github.com/Gustavo-b017"> Github </a>
  
## <a href="##-Indice"> Indice </a>
