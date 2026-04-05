# Calcpad

O Calcpad é um software gratuito para cálculos matemáticos e de engenharia. Ele representa uma calculadora programável flexível e moderna com um gerador de relatórios em Html. É simples e fácil de usar, mas também inclui muitos recursos avançados:

  * números reais e complexos (formatos retangular e polar-fasor);
  * unidades de medida (SI, Imperial e USCS);
  * vetores e matrizes: retangulares, simétricas, coluna, diagonais, triangulares superiores/inferiores;
  * variáveis e unidades personalizadas;
  * biblioteca integrada com funções matemáticas comuns;
  * funções de vetores e matrizes:
      * funções de dados: busca, consulta, ordenação, contagem, etc.;
      * funções de agregação: mín, máx, soma, soma dos quadrados (sumsq), srss, média, média (geométrica) do produto, etc.;
      * funções matemáticas: norma, condição, determinante, posto (rank), traço, transposta, adjunta e cofator, inversa, fatoração (Cholesky, LDLT, LU, QR e SVD), autovalores/vetores e sistemas lineares de equações;
  * funções personalizadas de múltiplos parâmetros f(x; y; z; …);
  * métodos numéricos poderosos para busca de raízes e extremos, integração e diferenciação numérica;
  * procedimentos de soma finita, produto e iteração, séries de Fourier e FFT;
  * módulos, macros e variáveis de texto (string);
  * leitura e escrita de dados de/para arquivos de texto, CSV e Excel;
  * controle de fluxo de programa com condições e loops;
  * "títulos" e comentários de 'texto' entre aspas;
  * suporte para Html e CSS em comentários para formatação rica;
  * plotagem de funções, imagens, tabelas, desenhos paramétricos em SVG, etc.;
  * geração automática de formulários Html para entrada de dados;
  * relatórios Html com aparência profissional para visualização e impressão;
  * exportação para documentos Word (\*.docx) e PDF;
  * substituição de variáveis e arredondamento inteligente de números;
  * controle de visibilidade da saída e recolhimento de conteúdo;
  * suporte para formatos de arquivo de texto simples (\*.txt, \*.cpd) e binário (\*.cpdz).

Este software é desenvolvido utilizando a linguagem de programação C\# e as mais recentes tecnologias de computação. Ele analisa automaticamente a entrada, substitui as variáveis, calcula as expressões e exibe o resultado. Todos os resultados são enviados para um relatório Html de aparência profissional para visualização e impressão.

## Áreas de aplicação

Este software é adequado para engenheiros e outros profissionais que precisam realizar cálculos repetitivos e apresentá-los em documentação oficial, como memórias de cálculo. Eles podem automatizar essa tarefa de forma eficiente criando planilhas Calcpad poderosas e confiáveis. Também pode ajudar professores a preparar exemplos de cálculo, artigos, manuais, livros, etc. Alunos podem usá-lo para resolver diversos problemas, preparar trabalhos de casa, teses, etc.

## Instalação

Um novo instalador será distribuído em momento oportuno (Após tradução da interface)
O software requer um computador de 64 bits com Windows 10/11 e [Microsoft .NET Desktop Runtime 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0).

## Licenciamento e termos de uso

Este software é gratuito para uso comercial e não comercial. É distribuído sob a licença MIT:

Copyright © 2025 PROEKTSOFT EOOD®

É concedida permissão, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e arquivos de documentação associados (o "Software"), para lidar com o Software sem restrição, incluindo, sem limitação, os direitos de usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do Software, e permitir que as pessoas a quem o Software é fornecido o façam, sujeito às seguintes condições:

O aviso de copyright acima e este aviso de permissão deverão ser incluídos em todas as cópias ou partes substanciais do Software.

O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO, EXPRESSA OU IMPLÍCITA, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO, ADEQUAÇÃO A UM PROPÓSITO ESPECÍFICO E NÃO INFRAÇÃO. EM NENHUM CASO OS AUTORES OU TITULARES DE COPYRIGHT SERÃO RESPONSÁVEIS POR QUALQUER REIVINDICAÇÃO, DANOS OU OUTRA RESPONSABILIDADE, SEJA EM UMA AÇÃO DE CONTRATO, ATO ILÍCITO OU DE OUTRA FORMA, DECORRENTE DE, FORA DE OU EM CONEXÃO COM O SOFTWARE OU O USO OU OUTRAS NEGOCIAÇÕES NO SOFTWARE.

Quaisquer scripts desenvolvidos com Calcpad são de propriedade dos respectivos autores. Eles podem ser usados sem limitações adicionais, exceto aquelas designadas pelos próprios autores.

### Agradecimentos

Este projeto utiliza alguns componentes, softwares e designs adicionais de terceiros. Eles são redistribuídos gratuitamente, sob as condições de licença fornecidas pelos respectivos autores.

1.  Nedelcho Ganchovski e a Proektsoft BG, desenvolvedor original do software
2.  Os novos e belos ícones foram criados usando [icons8.com](https://icons8.com/).
3.  A exportação para PDF foi possível graças ao projeto [wkhtmltopdf.org](https://wkhtmltopdf.org/).
4.  Alguns símbolos são exibidos usando a família de fontes Jost\* da [indestructible type\*](https://indestructibletype.com/), sob a [licença de fonte aberta SIL](https://scripts.sil.org/cms/scripts/page.php?item_id=OFL_web). Os colchetes foram ligeiramente modificados para atender às necessidades da aplicação.

## Como funciona

O software é rápido e fácil de usar. Basta seguir estes passos simples:

1. **Insira** texto e fórmulas na caixa "**Code**" à esquerda.
2. Pressione **F5** ou clique em <img alt="Play" height="24" src="https://raw.githubusercontent.com/hildebrandopsj/calcpad/main/Help/Images/Play.png"> para calcular. Os resultados aparecerão na caixa "**Output**" à direita como um **relatório** Html formatado profissionalmente.
3. Clique em <img alt="PrintPreview" height="24" src="https://raw.githubusercontent.com/hildebrandopsj/calcpad/main/Help/Images/PrintPreview.png"> para **imprimir** ou em <img alt="Copy" height="24" src="https://raw.githubusercontent.com/hildebrandopsj/calcpad/main/Help/Images/Copy.png"> para **copiar** a saída.
   Você também pode **exportar** para um documento **Html** <img alt="Html" height="24" src="https://raw.githubusercontent.com/hildebrandopsj/calcpad/main/Help/Images/Save.png">, **PDF** <img alt="PDF" height="24" src="https://raw.githubusercontent.com/hildebrandopsj/calcpad/main/Help/Images/Pdf.png"> ou **MS Word** <img alt="Word" height="24" src="https://raw.githubusercontent.com/hildebrandopsj/calcpad/main/Help/Images/Word.png">.

## A linguagem

O Calcpad utiliza uma linguagem de programação simples que inclui os seguintes elementos:

  * Números reais: dígitos 0 - 9 e ponto decimal ".";  
  * Números complexos: re ± imi (ex: 3 - 2i);  
  * Vetores: [v₁; v₂; v₃; …; vₙ];  
  * Matrizes: [M₁₁; M₁₂; … ; M₁ₙ | M₂₁; M₂₂; … ; M₂ₙ | … | Mₘ₁; Mₘ₂; … ; Mₘₙ]  
  * Variáveis:  
     - todas as letras Unicode;  
     - dígitos: 0 - 9;  
     - vírgula: " , ";  
     - símbolos especiais: ′ , ″ , ‴ , ⁗ , ‾ , ø , Ø , ° , ∡ ;  
     - sobrescritos: ⁰ , ¹ , ² , ³ , ⁴ , ⁵ , ⁶ , ⁷ , ⁸ , ⁹ , ⁿ , ⁺ , ⁻ ;  
     - subscritos: ₀ , ₁ , ₂ , ₃ , ₄ , ₅ , ₆ , ₇ , ₈ , ₉ , ₊ , ₋ , ₌ , ₍ , ₎;  
     - " \_ " para subscrito;  
    Qualquer nome de variável deve começar com uma letra. Os nomes diferenciam maiúsculas de minúsculas (case sensitive).  
  * Operadores:  
     "**\!**" - fatorial;  
     "**^**" - expoente;  
     "**/**" - divisão;  
     "**÷**" - força barra de divisão no modo inline e barra (//) no modo pro;  
     "**\\**" - divisão inteira;  
     "**⦼**" - módulo (resto);  
     "**\***" - multiplicação;  
     "**-**" - menos;  
     "**+**" - mais;  
     "**≡**" - igual a;  
     "**≠**" - diferente de;  
     "**\<**" - menor que;  
     "**\>**" - maior que;  
     "**≤**" - menor ou igual;  
     "**≥**" - maior ou igual;  
     "**∧**" - "E" lógico;  
     "**∨**" - "OU" lógico;  
     "**⊕**" - "XOR" lógico;  
     "**∠**" - fasor A∠φ (\<\<);  
     "**=**" - atribuição ou definição de variável, função ou macro;  
     "**←**" - atribuição para um nível externo ou variável global em bloco (\<\*);  
  * Funções personalizadas do tipo f (x; y; z; ... );  
  * Funções integradas:  
     Trigonométricas:  
      **sin**(x)  - seno;  
      **cos**(x)  - cosseno;  
      **tan**(x)  - tangente;  
      **csc**(x)  - cossecante;  
      **sec**(x)  - secante;  
      **cot**(x)  - cotangente;  
     Hiperbólicas:  
      **sinh**(x) - seno hiperbólico;  
      **cosh**(x) - cosseno hiperbólico;  
      **tanh**(x) - tangente hiperbólica;  
      **csch**(x) - cossecante hiperbólica;  
      **sech**(x) - secante hiperbólica;  
      **coth**(x) - cotangente hiperbólica;  
     Trigonométricas Inversas:  
      **asin**(x) - arco seno;  
      **acos**(x) - arco cosseno;  
      **atan**(x) - arco tangente;  
      **atan2**(x; y) - o ângulo cuja tangente é o quociente entre y e x;  
      **acsc**(x) - arco cossecante;  
      **asec**(x) - arco secante;  
      **acot**(x) - arco cotangente;  
     Hiperbólicas Inversas:  
      **asinh**(x) - arco seno hiperbólico;  
      **acosh**(x) - arco cosseno hiperbólico;  
      **atanh**(x) - arco tangente hiperbólico;  
      **acsch**(x) - arco cossecante hiperbólico;  
      **asech**(x) - arco secante hiperbólico;  
      **acoth**(x) - arco cotangente hiperbólico;  
     Logarítmicas, exponenciais e raízes:  
      **log**(x)   - logaritmo decimal;  
      **ln**(x)    - logaritmo natural;  
      **log\_2**(x) - logaritmo binário;  
      **exp**(x)   - exponencial natural;  
      **sqr**(x) ou **sqrt**(x) - raiz quadrada;  
      **cbrt**(x) - raiz cúbica;  
      **root**(x; n) - raiz enésima;  
     Arredondamento:  
      **round**(x) - arredonda para o inteiro mais próximo;  
      **floor**(x) - arredonda para o inteiro menor (em direção a -∞);  
      **ceiling**(x) - arredonda para o inteiro maior (em direção a +∞);  
      **trunc**(x) - arredonda para o inteiro menor (em direção a zero);  
     Inteiros:  
      **mod**(x; y) - o resto de uma divisão inteira;  
      **gcd**(x; y; z...) - o máximo divisor comum de vários inteiros;  
      **lcm**(x; y; z...) - o mínimo múltiplo comum de vários inteiros;  
     Complexos:  
      **re**(z)    - a parte real de um número complexo;  
      **im**(z)    - a parte imaginária de um número complexo;  
      **abs**(z)   - valor absoluto/módulo;  
      **phase**(z) - a fase de um número complexo;  
      **conj**(z)  - o conjugado de um número complexo;  
     Agregação e interpolação:  
      **min**(x; y; z...) - mínimo de múltiplos valores;  
      **max**(x; y; z...) - máximo de múltiplos valores;  
      **sum**(x; y; z...) - soma de múltiplos valores = x + y + z...;  
      **sumsq**(x; y; z...) - soma dos quadrados = x² + y² + z²...;  
      **srss**(x; y; z...) - raiz quadrada da soma dos quadrados = sqrt(x² + y² + z²...);  
      **average**(x; y; z...) - média de múltiplos valores = (x + y + z...)/n;  
      **product**(x; y; z...) - produto de múltiplos valores = x·y·z...;  
      **mean**(x; y; z...) - média geométrica = raiz enésima(x·y·z...);  
      **take**(n; a; b; c...) - retorna o n-ésimo elemento da lista;  
      **line**(x; a; b; c...) - interpolação linear;  
      **spline**(x; a; b; c...) - interpolação por spline de Hermite;  
     Condicional e lógico:  
      **if**(*cond*; *valor-se-verdade*; *valor-se-falso*) - avaliação condicional;  
      **switch**(*cond1*; *valor1*; *cond2*; *valor2*; … ; *padrão*) - avaliação seletiva;  
      **not**(x) - "NÃO" lógico;  
      **and**(x; y; z...) - "E" lógico;  
      **or**(x; y; z...) - "OU" lógico;  
      **xor**(x; y; z...) - "XOR" lógico;  
     Outros:  
      **sign**(x) - o sinal de um número;  
      **random**(x) - número aleatório entre 0 e x;  
      **getunits**(x) - obtém as unidades de x sem o valor. Retorna 1 se x for adimensional;  
      **setunits**(x; u) - define as unidades u para x, onde x pode ser escalar, vetor ou matriz;  
      **clrunits**(x) - remove as unidades de um escalar, vetor ou matriz x;  
      **hp**(x) - converte x para seu tipo equivalente de alto desempenho (hp);  
      **ishp**(x) - verifica se o tipo de x é um vetor ou matriz de alto desempenho (hp);  
     Vetor:  
      Criação:  
      **vector**(n) - cria um vetor vazio com comprimento n;  
      **vector\_hp**(n) - cria um vetor vazio de alto desempenho (hp) com comprimento n;  
      **range**(x1; xn; s) - cria um vetor com valores de x1 a xn com passo s;  
      **range\_hp**(x1; xn; s) - cria um vetor hp a partir de um intervalo de valores como acima;  
      \<ins\>Estrutural:\</ins\>  
      **len**(v) - retorna o comprimento do vetor v;  
      **size**(v) - o tamanho real do vetor v - o índice do último elemento não nulo;  
      **resize**(v; n) - define um novo comprimento n para o vetor v;  
      **fill**(v; x) - preenche o vetor v com o valor x;  
      **join**(A; b; c…) - cria um vetor unindo os argumentos: matrizes, vetores e escalares;  
      **slice**(v; i₁; i₂) - retorna a parte do vetor v delimitada pelos índices i₁ e i₂ inclusive;  
      **first**(v; n) - os primeiros n elementos do vetor v;  
      **last**(v; n) - os últimos n elementos do vetor v;  
      **extract**(v; i) - extrai os elementos de v cujos índices estão contidos em i;  
      \<ins\>Dados:\</ins\>  
      **sort**(v) - ordena os elementos do vetor v em ordem crescente;  
      **rsort**(v) - ordena os elementos do vetor v em ordem decrescente;  
      **order**(v) - os índices do vetor v, organizados pela ordem crescente de seus elementos;  
      **revorder**(v) - os índices do vetor v, organizados pela ordem decrescente de seus elementos;  
      **reverse**(v) - um novo vetor contendo os elementos de v em ordem inversa;  
      **count**(v; x; i) - o número de elementos em v, após o i-ésimo, que são iguais a x;  
      **search**(v; x; i)- o índice do primeiro elemento em v, após o i-ésimo, que é igual a x;  
      **find**(v; x; i) ou  
      **find\_eq**(v; x; i) - os índices de todos os elementos em v, após o i-ésimo, que são = x;  
      **find\_ne**(v; x; i) - os índices de todos os elementos em v, após o i-ésimo, que são ≠ x;  
      **find\_lt**(v; x; i) - os índices de todos os elementos em v, após o i-ésimo, que são \< x;  
      **find\_le**(v; x; i) - os índices de todos os elementos em v, após o i-ésimo, que são ≤ x;  
      **find\_gt**(v; x; i) - os índices de todos os elementos em v, após o i-ésimo, que são \> x;  
      **find\_ge**(v; x; i) - os índices de todos os elementos em v, após o i-ésimo, que são ≥ x;  
      **lookup**(a; b; x) ou  
      **lookup\_eq**(a; b; x) - todos os elementos em a para os quais os respectivos elementos em b são = x;  
      **lookup\_ne**(a; b; x) - todos os elementos em a para os quais os respectivos elementos em b são ≠ x;  
      **lookup\_lt**(a; b; x) - todos os elementos em a para os quais os respectivos elementos em b são \< x;  
      **lookup\_le**(a; b; x) - todos os elementos em a para os quais os respectivos elementos em b são ≤ x;  
      **lookup\_gt**(a; b; x) - todos os elementos em a para os quais os respectivos elementos em b são \> x;  
      **lookup\_ge**(a; b; x) - todos os elementos em a para os quais os respectivos elementos em b são ≥ x;  
      \<ins\>Matemática:\</ins\>  
      **norm\_1**(v) - norma L1 (Manhattan) do vetor v;  
      **norm**(v) ou  
      **norm\_2**(v) ou  
      **norm\_e**(v) - norma L2 (Euclidiana) do vetor v;  
      **norm\_p**(v; p) - norma Lp do vetor v;  
      **norm\_i**(v) - norma L∞ (infinito) do vetor v;  
      **unit**(v) - o vetor v normalizado (com norma L2 = 1);  
      **dot**(a; b) - produto escalar de dois vetores a e b;  
      **cross**(a; b) - produto vetorial de dois vetores a e b (com comprimento 2 ou 3);  
     Matriz:  
      \<ins\>Criação:\</ins\>  
      **matrix**(m; n) - cria uma matriz vazia com dimensões m⨯n;  
      **identity**(n) - cria uma matriz identidade com dimensões n⨯n;  
      **diagonal**(n; d) - cria uma matriz diagonal n⨯n e preenche a diagonal com o valor d;  
      **column**(m; c) - cria uma matriz coluna com dimensões m⨯1, preenchida com o valor c;  
      **utriang**(n) - cria uma matriz triangular superior com dimensões n⨯n;  
      **ltriang**(n) - cria uma matriz triangular inferior com dimensões n⨯n;  
      **symmetric**(n) - cria uma matriz simétrica com dimensões n⨯n;  
      **matrix\_hp**(m; n) - cria uma matriz de alto desempenho com dimensões m⨯n;  
      **identity\_hp**(n) - cria uma matriz identidade de alto desempenho com dimensões n⨯n;  
      **diagonal\_hp**(n; d) - cria uma matriz diagonal hp n⨯n preenchida com valor d;  
      **column\_hp**(m; c) - cria uma matriz coluna hp m⨯1 preenchida com valor c;  
      **utriang\_hp**(n) - cria uma matriz triangular superior hp n⨯n;  
      **ltriang\_hp**(n) - cria uma matriz triangular inferior hp n⨯n;  
      **symmetric\_hp**(n) - cria uma matriz simétrica hp com dimensões n⨯n;  
      **vec2diag**(v) - cria uma matriz diagonal a partir dos elementos do vetor v;  
      **vec2row**(v) - cria uma matriz linha a partir dos elementos do vetor v;  
      **vec2col**(v) - cria uma matriz coluna a partir dos elementos do vetor v;  
      **join\_cols**(c₁; c₂; c₃…) - cria uma nova matriz unindo vetores coluna;  
      **join\_rows**(r₁; r₂; r₃…) - cria uma nova matriz unindo vetores linha;  
      **augment**(A; B; C…) - cria uma nova matriz anexando matrizes A; B; C lado a lado;  
      **stack**(A; B; C…) - cria uma nova matriz empilhando matrizes A; B; C uma abaixo da outra;  
      \<ins\>Estrutural:\</ins\>  
      **n\_rows**(M) - número de linhas na matriz M;  
      **n\_cols**(M) - número de colunas na matriz M;  
      **mresize**(M; m; n) - define novas dimensões m e n para a matriz M;  
      **mfill**(M; x) - preenche a matriz M com o valor x;  
      **fill\_row**(M; i; x) - preenche a i-ésima linha da matriz M com o valor x;  
      **fill\_col**(M; j; x) - preenche a j-ésima coluna da matriz M com o valor x;  
      **copy**(A; B; i; j) - copia todos os elementos de A para B, começando nos índices i e j de B;  
      **add**(A; B; i; j) - soma todos os elementos de A aos de B, começando nos índices i e j de B;  
      **row**(M; i) - extrai a i-ésima linha da matriz M como um vetor;  
      **col**(M; j) - extrai a j-ésima coluna da matriz M como um vetor;  
      **extract\_rows**(M; i) - extrai as linhas da matriz M cujos índices estão contidos no vetor i;  
      **extract\_cols**(M; j) - extrai as colunas da matriz M cujos índices estão contidos no vetor j;  
      **diag2vec**(M) - extrai os elementos da diagonal da matriz M para um vetor;  
      **submatrix**(M; i₁; i₂; j₁; j₂) - extrai uma submatriz de M, delimitada pelas linhas i₁ e i₂ e colunas j₁ e j₂, incl.;  
      \<ins\>Dados:\</ins\>  
      **sort\_cols**(M; i) - ordena as colunas de M com base nos valores da linha i em ordem crescente;  
      **rsort\_cols**(M; i) - ordena as colunas de M com base nos valores da linha i em ordem decrescente;  
      **sort\_rows**(M; j) - ordena as linhas de M com base nos valores da coluna j em ordem crescente;  
      **rsort\_rows**(M; j) - ordena as linhas de M com base nos valores da coluna j em ordem decrescente;  
      **order\_cols**(M; i) - os índices das colunas de M baseados na ordenação dos valores da linha i em ordem crescente;  
      **revorder\_cols**(M; i) - os índices das colunas de M baseados na ordenação dos valores da linha i em ordem decrescente;  
      **order\_rows**(M; j) - os índices das linhas de M baseados na ordenação dos valores na coluna j em ordem crescente;  
      **revorder\_rows**(M; j) - os índices das linhas de M baseados na ordenação dos valores na coluna j em ordem decrescente;  
      **mcount**(M; x) - número de ocorrências do valor x na matriz M;  
      **msearch**(M; x; i; j) - vetor com os dois índices da primeira ocorrência de x na matriz M, partindo dos índices i e j;  
      **mfind**(M; x) ou  
      **mfind\_eq**(M; x) - os índices de todos os elementos em M que são = x;  
      **mfind\_ne**(M; x) - os índices de todos os elementos em M que são ≠ x;  
      **mfind\_lt**(M; x) - os índices de todos os elementos em M que são \< x;  
      **mfind\_le**(M; x) - os índices de todos os elementos em M que são ≤ x;  
      **mfind\_gt**(M; x) - os índices de todos os elementos em M que são \> x;  
      **mfind\_ge**(M; x) - os índices de todos os elementos em M que são ≥ x;  
      **hlookup**(M; x; i₁; i₂) ou  
      **hlookup\_eq**(M; x; i₁; i₂) - os valores da linha i₂ de M, para os quais os elementos na linha i₁ são = x;  
      **hlookup\_ne**(M; x; i₁; i₂) - os valores da linha i₂ de M, para os quais os elementos na linha i₁ são ≠ x;  
      **hlookup\_lt**(M; x; i₁; i₂) - os valores da linha i₂ de M, para os quais os elementos na linha i₁ são \< x;  
      **hlookup\_le**(M; x; i₁; i₂) - os valores da linha i₂ de M, para os quais os elementos na linha i₁ são ≤ x;  
      **hlookup\_gt**(M; x; i₁; i₂) - os valores da linha i₂ de M, para os quais os elementos na linha i₁ são \> x;  
      **hlookup\_ge**(M; x; i₁; i₂) - os valores da linha i₂ de M, para os quais os elementos na linha i₁ são ≥ x;  
      **vlookup**(M; x; j₁; j₂) ou  
      **vlookup\_eq**(M; x; j₁; j₂) - os valores da coluna j₂ de M, para os quais os elementos na coluna j₁ são = x;  
      **vlookup\_ne**(M; x; j₁; j₂) - os valores da coluna j₂ de M, para os quais os elementos na coluna j₁ são ≠ x;  
      **vlookup\_lt**(M; x; j₁; j₂) - os valores da coluna j₂ de M, para os quais os elementos na coluna j₁ são \< x;  
      **vlookup\_le**(M; x; j₁; j₂) - os valores da coluna j₂ de M, para os quais os elementos na coluna j₁ são ≤ x;  
      **vlookup\_gt**(M; x; j₁; j₂) - os valores da coluna j₂ de M, para os quais os elementos na coluna j₁ são \> x;  
      **vlookup\_ge**(M; x; j₁; j₂) - os valores da coluna j₂ de M, para os quais os elementos na coluna j₁ são ≥ x;  
      \<ins\>Matemática:\</ins\>  
      **hprod**(A; B) - produto de Hadamard das matrizes A e B;  
      **fprod**(A; B) - produto de Frobenius das matrizes A e B;  
      **kprod**(A; B) - produto de Kronecker das matrizes A e B;  
      **mnorm\_1**(M) - norma L1 da matriz M;  
      **mnorm**(M) ou  
      **mnorm\_2**(M) - norma L2 da matriz M;  
      **mnorm\_e**(M) - norma de Frobenius da matriz M;  
      **mnorm\_i**(M) - norma L∞ da matriz M;  
      **cond\_1**(M) - número de condição de M baseado na norma L1;  
      **cond**(M) ou  
      **cond\_2**(M) - número de condição de M baseado na norma L2;  
      **cond\_e**(M) - número de condição de M baseado na norma de Frobenius;  
      **cond\_i**(M) - número de condição de M baseado na norma L∞;  
      **det**(M) - determinante da matriz M;  
      **rank**(M) - posto da matriz M;  
      **trace**(M) - traço da matriz M;  
      **transp**(M) - transposta da matriz M;  
      **adj**(M) - adjunta da matriz M;  
      **cofactor**(M) - matriz de cofatores de M;  
      **eigenvals**(M; n\_e) - os primeiros n\_e (ou todos se omitido) autovalores da matriz M como um vetor;  
      **eigenvecs**(M; n\_e) - os primeiros n\_e (ou todos se omitido) autovetores da matriz M como uma matriz row-major;  
      **eigen**(M; n\_e) - os primeiros n\_e (ou todos se omitido) autovalores e autovetores de M como uma matriz row-major;  
      **cholesky**(M) - decomposição de Cholesky de uma matriz M simétrica e definida positiva;  
      **lu**(M) - decomposição LU da matriz M;  
      **qr**(M) - decomposição QR da matriz M;  
      **svd**(M) - decomposição em valores singulares (SVD) de M;  
      **inverse**(M) - inversa da matriz M;  
      **lsolve**(A; b) - resolve o sistema de equações lineares Ax = b usando decomposição LDLT para matrizes simétricas e LU para não simétricas;  
      **clsolve**(A; b) - resolve a equação matricial linear Ax = b com matriz A simétrica e definida positiva usando decomposição de Cholesky;  
      **slsolve**(A; b) - resolve a equação matricial linear Ax = b com matriz A hp simétrica e definida positiva usando o método do gradiente conjugado precondicionado (PCG);  
      **msolve**(A; B) - resolve a equação matricial generalizada AX = B usando decomposição LDLT para matrizes simétricas e LU para não simétricas;  
      **cmsolve**(A; B) - resolve a equação matricial generalizada AX = B com matriz A simétrica e definida positiva usando decomposição de Cholesky;  
      **smsolve**(A; B) - resolve a equação matricial generalizada AX = B com matriz A hp simétrica e definida positiva usando o método PCG;  
      **matmul**(A; B) - multiplicação rápida de matrizes hp quadradas usando o algoritmo paralelo de Winograd. O operador de multiplicação A\*B o utiliza automaticamente para todas as matrizes hp quadradas de tamanho 10 ou superior;  
      **fft**(M) - realiza a transformada rápida de Fourier da matriz row-major M. Deve ter uma linha para dados reais e duas linhas para complexos;  
      **ift**(M) - realiza a transformada inversa de Fourier da matriz row-major M. Deve ter uma linha para dados reais e duas linhas para complexos;  
      **\<ins\>Interpolação dupla:\</ins\>**  
      **take**(x; y; M) - retorna o elemento da matriz M nos índices x e y;  
      **line**(x; y; M) - interpolação linear dupla dos elementos da matriz M baseada nos valores de x e y;  
      **spline**(x; y; M) - interpolação dupla por spline de Hermite dos elementos da matriz M baseada nos valores de x e y.  
      *Tol* - tolerância alvo para o resolvedor iterativo PCG.  
  * Comentários: "Título" ou 'texto' em aspas duplas ou simples, respectivamente. HTML, CSS, JS e SVG são permitidos.
  * Gráficos e plotagem:  
     $Plot { f(x) @ x = a : b } - gráfico simples;  
    &emsp;$Plot { x(t) | y(t) @ t = a : b } - paramétrico;  
     $Plot { f1(x) & f2(x) & ... @ x = a : b } - múltiplos;  
    &emsp;$Plot { x1(t) | y1(t) & x2(t) | y2(t) & ... @ x = a : b } - múltiplos paramétricos;  
     $Map { f(x; y) @ x = a : b & y = c : d }  - mapa de cores 2D de uma superfície 3D;  
     PlotHeight - altura da área do gráfico em pixels;  
     PlotWidth - largura da área do gráfico em pixels;  
     PlotSVG - desenha gráficos em formato vetorial (SVG);  
     PlotAdaptive - usa malha adaptativa (= 1) para plotagem de funções ou uniforme (= 0);  
     PlotStep - o tamanho da malha para plotagem de mapa;  
     PlotPalette - o número da paleta de cores a ser usada para gráficos de superfície (0-9);  
     PlotShadows - desenha gráficos de superfície com sombras;  
     PlotSmooth - transição suave de cores (= 1) ou isobandas (= 0) para gráficos de superfície;  
     PlotLightDir - direção da fonte de luz (0-7) no sentido horário.  
  * Métodos iterativos e numéricos:  
     $Root { f(x) = const @ x = a : b } - busca de raiz para f(x) = const;  
    &emsp;$Root { f(x) @ x = a : b } - busca de raiz para f(x) = 0;  
     $Find { f(x) @ x = a : b } - similar ao anterior, mas não exige que x seja uma solução precisa;  
    &emsp;$Sup { f(x) @ x = a : b } - máximo local de uma função;  
     $Inf { f(x) @ x = a : b } - mínimo local de uma função;  
    &emsp;$Area { f(x) @ x = a : b } - integração numérica adaptativa de Gauss-Lobatto;  
     $Integral { f(x) @ x = a : b } - integração numérica Tanh-Sinh;  
    &emsp;$Slope { f(x) @ x = a } - diferenciação numérica por extrapolação de Richardson;  
     $Derivative { f(x) @ x = a } - diferenciação numérica por método de passo complexo;  
    &emsp;$Sum { f(k) @ k = a : b } - soma iterativa;  
     $Product { f(k) @ k = a : b } - produto iterativo;  
    &emsp;$Repeat { f(k) @ k = a : b } - bloco de expressão iterativo com contador;  
     $While { condição; expressões } - bloco de expressão iterativo com condição;  
    &emsp;$Block { expressões } - bloco de expressão multilinha;  
     $Inline { expressões } - bloco de expressão inline;  
     Precision - precisão relativa para métodos numéricos \[10\<sup\>-2\</sup\>; 10\<sup\>-16\</sup\>\] (padrão é 10\<sup\>-12\</sup\>)  
  * Controle de fluxo de programa:  
     Simples:  
      \#if *condição*  
       *Seu código aqui*  
      \#end if  
     Alternativo:  
      \#if *condição*  
       *Seu código aqui*  
      \#else  
       *Outro código*  
      \#end if  
     Completo:  
      \#if *condição1*  
       *Seu código aqui*  
      \#else if *condição2*  
       *Seu código aqui*  
      \#else  
       *Outro código*  
      \#end if  
    Você pode adicionar ou omitir quantos "\#else if" forem necessários. Apenas um "\#else" é permitido (também opcional).  
  * Blocos de iteração:  
     Simples:  
      \#repeat *número de repetições*  
       *Seu código aqui*  
      \#loop  
     Com interrupção/continuação condicional:  
      \#repeat *número de repetições*  
       *Seu código aqui*  
       \#if *condição*  
        \#break ou \#continue  
       \#end if  
       *Mais código*  
      \#loop  
     Com contador:  
      \#for contador = início : fim  
       *Seu código aqui*  
      \#loop  
     Com condição:  
      \#while *condição*  
       *Seu código aqui*  
      \#loop  
  * Módulos e macros/variáveis de texto:  
     Módulos:  
      \#include *nome\_do\_arquivo* - inclui arquivo externo (módulo);  
      \#local - inicia seção local (não será incluída);  
      \#global - inicia seção global (será incluída);  
     Variável de texto inline:  
      \#def *nome\_da\_variavel$* = *conteúdo*  
    &emsp;Variável de texto multilinha:  
    &emsp;&emsp;#def *nome_da_variavel$*  
       *conteúdo linha 1*  
       *conteúdo linha 2*  
       ...  
      \#end def  
     Macro de texto inline:  
      \#def *nome\_da\_macro$*(*param1$*; *param2$*;...) = *conteúdo*  
    &emsp;Macro de texto multilinha:  
    &emsp;&emsp;#def *nome_da_macro$*(*param1$*; *param2$*;...)  
       *conteúdo linha 1*  
       *conteúdo linha 2*  
       ...  
      \#end def  
  * Importação/Exportação de dados externos:  
     Arquivos de Texto/CSV:  
      \#read M from arquivo.txt@R1C1:R2C2 TYPE=R SEP=',' - lê matriz M de arquivo texto/CSV;  
      \#write M to arquivo.txt@R1C1:R2C2 TYPE=N SEP=',' - escreve matriz M em arquivo texto/CSV;  
      \#append M to arquivo.txt@R1C1:R2C2 TYPE=N SEP=',' - anexa matriz M em arquivo texto/CSV;  
     Arquivos Excel (xlsx e xlsm):  
      \#read M from arquivo.xlsx@Planilha1\!A1:B2 TYPE=R - lê matriz M de arquivo Excel;  
      \#write M to arquivo.xlsx@Planilha1\!A1:B2 TYPE=N - escreve matriz M em arquivo Excel;  
      \#append M to arquivo.xlsx@Planilha1\!A1:B2 TYPE=N - anexa matriz M em arquivo Excel (mesmo que write);  
     Planilha, intervalo, TYPE e SEP podem ser omitidos.  
     Para o comando \#read, TYPE pode ser [R|D|C|S|U|L|V].  
     Para comandos \#write e \#append, TYPE pode ser Y ou N.  
  * Proteção de escrita: \#const - declara uma variável ou função constante (somente leitura);  
  * Controle de saída:  
     \#hide - oculta o conteúdo do relatório;  
     \#show - sempre mostra o conteúdo (padrão);  
     \#pre  - mostra o conteúdo seguinte apenas antes dos cálculos;  
     \#post - mostra o conteúdo seguinte apenas após os cálculos;  
     \#val  - mostra apenas o resultado final, sem a equação;  
     \#equ  - mostra equações completas e resultados (padrão);  
     \#noc  - mostra apenas equações sem resultados (sem cálculos);  
     \#nosub  - não substitui variáveis (sem substituição);  
     \#novar  - mostra equações apenas com valores substituídos (sem variáveis);  
     \#varsub - mostra equações com variáveis e valores substituídos (padrão);  
     \#split - divide equações que não cabem em uma única linha;  
     \#wrap - quebra equações que não cabem em uma única linha (padrão);  
     \#round n - arredonda a saída para n dígitos após o ponto decimal;  
     \#round default - restaura o arredondamento para as configurações padrão;  
     \#format FFFF - especifica uma string de formato personalizada;  
     \#format default - restaura a formatação padrão;  
     \#md on - habilita markdown nos comentários;  
     \#md off - desabilita markdown nos comentários;  
     \#phasor - define formato de saída de complexos para polar fasorial: A∠φ;  
     \#complex - define formato de saída de complexos para algébrico cartesiano: a + bi.  
     Cada um dos comandos acima é efetivo após a linha atual até o fim do relatório ou outro comando que o sobrescreva.  
  * Pontos de interrupção (breakpoints) para execução passo a passo:  
     \#pause - calcula até a linha atual e aguarda retomada manual;  
     \#input - renderiza um formulário de entrada até a linha atual e aguarda entrada do usuário.  
  * Seletores de unidades trigonométricas: \#deg - graus, \#rad - radianos, \#gra - grados;  
  * Separador para unidades de destino: |, por exemplo: `3ft + 12in|cm` mostrará 121,92 cm;  
  * Adimensionais: %, ‰, ‱, pcm, ppm, ppb, ppt, ppq;  
  * Unidades de ângulo: °, ′, ″, deg, rad, grad, rev;  
  * Unidades métricas (SI e compatíveis):  
     Massa: g, hg, kg, t, kt, Mt, Gt, dg, cg, mg, μg, Da, u;  
     Comprimento: m, km, dm, cm, mm, μm, nm, pm, AU, ly;  
     Tempo: s, ms, μs, ns, ps, min, h, d, w, y;  
     Frequência: Hz, kHz, MHz, GHz, THz, mHz, μHz, nHz, pHz, rpm;  
     Velocidade: kmh;  
     Corrente elétrica: A, kA, MA, GA, TA, mA, μA, nA, pA;  
     Temperatura: °C, Δ°C, K;  
     Quantidade de substância: mol;  
     Intensidade luminosa: cd;  
     Área: a, daa, ha;  
     Volume: L, daL, hL, dL, cL, mL, μL, nL, pL;  
     Força: dyn N, daN, hN, kN, MN, GN, TN, gf, kgf, tf;  
     Momento: Nm, kNm;  
     Pressão: Pa, daPa, hPa, kPa, MPa, GPa, TPa, dPa, cPa, mPa, μPa, nPa, pPa,  
        bar, mbar, μbar, atm, at, Torr, mmHg;  
     Viscosidade: P, cP, St, cSt;  
     Energia/trabalho: J, kJ, MJ, GJ, TJ, mJ, μJ, nJ, pJ,  
        Wh, kWh, MWh, GWh, TWh, mWh, μWh, nWh, pWh  
        eV, keV, MeV, GeV, TeV, PeV, EeV, cal, kcal, erg;  
     Potência: W, kW, MW, GW, TW, mW, μW, nW, pW, hpM, ks;  
        VA, kVA, MVA, GVA, TVA, mVA, μVA, nVA, pVA,  
        VAR, kVAR, MVAR, GVAR, TVAR, mVAR, μVAR, nVAR, pVAR, hpM, ks;  
     Carga elétrica: C, kC, MC, GC, TC, mC, μC, nC, pC, Ah, mAh;  
     Potencial: V, kV, MV, GV, TV, mV, μV, nV, pV;  
     Capacitância: F, kF, MF, GF, TF, mF, μF, nF, pF;  
     Resistência: Ω, kΩ, MΩ, GΩ, TΩ, mΩ, μΩ, nΩ, pΩ;  
     Condutância: S, kS, MS, GS, TS, mS, μS, nS, pS, ℧, k℧, M℧, G℧, T℧, m℧, μ℧, n℧, p℧;  
     Fluxo magnético: Wb , kWb, MWb, GWb, TWb, mWb, μWb, nWb, pWb;  
     Densidade de fluxo magnético: T, kT, MT, GT, TT, mT, μT, nT, pT;  
     Indutância: H, kH, MH, GH, TH, mH, μH, nH, pH;  
     Fluxo luminoso: lm;  
     Iluminância: lx;  
     Radioatividade: Bq, kBq, MBq, GBq, TBq, mBq, μBq, nBq, pBq, Ci, Rd;  
     Dose absorvida: Gy, kGy, MGy, GGy, TGy, mGy, μGy, nGy, pGy;  
     Dose equivalente: Sv, kSv, MSv, GSv, TSv, mSv, μSv, nSv, pSv;  
     Atividade catalítica: kat;  
  * Unidades não métricas (Imperial/US):  
     Massa: gr, dr, oz, lb (ou lbm, lb\_m), klb, kipm (ou kip\_m), st, qr,  
        cwt (ou cwt\_UK, cwt\_US), ton (ou ton\_UK, ton\_US), slug;  
     Comprimento: th, in, ft, yd, ch, fur, mi, ftm (ou ftm\_UK, ftm\_US),  
         cable (ou cable\_UK, cable\_US), nmi, li, rod, pole, perch, lea;  
     Velocidade: mph, knot;  
     Temperatura: °F, Δ°F, °R;  
     Área: rood, ac;  
     Volume, fluido: fl\_oz, gi, pt, qt, gal, bbl, ou:  
       fl\_oz\_UK, gi\_UK, pt\_UK, qt\_UK, gal\_UK, bbl\_UK,  
       fl\_oz\_US, gi\_US, pt\_US, qt\_US, gal\_US, bbl\_US,  
     Volume, seco: (US) pt\_dry, (US) qt\_dry, (US) gal\_dry, (US) bbl\_dry,  
       pk (ou pk\_UK, pk\_US), bu (or bu\_UK, bu\_US);  
     Força: ozf (ou oz\_f), lbf (ou lb\_f), kip (ou kipf, kip\_f), tonf (ou ton\_f), pdl;  
     Pressão: osi, osf psi, psf, ksi, ksf, tsi, tsf, inHg;  
     Energia/trabalho: BTU, therm, (ou therm\_UK, therm\_US), quad;  
     Potência: hp, hpE, hpS;  
  * Unidades personalizadas - .Nome = expressão.  
    Nomes podem incluir símbolos de moedas: €, £, ₤, ¥, ¢, ₽, ₹, ₩, ₪.  
