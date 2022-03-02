<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P1 - 16/02/2022</p>

Matrícula: 201802751
Nome: Alan Brito Barros

<p><font color=green>Nota 8,8</font></p>

1. Quanto ao objetivo do Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Qual o objetivo primário da atividade de teste de software? **O objetivo do teste de software é de detectar falhas, defeitos e qualquer tipo de comportamento inesperado que possa vir a ocorrer durante o funcionamento de um software.**
   <font color=orange>Parcialmente correto. Nota 0,25</font>
   2. (**0,5 ponto**) O que acontece, quando não se atinge este objetivo primário? **Quando não se testa um software de maneira adequada, chances são de erros não serem detectados, o que implica na construção de um software de baixa qualidade, confiabilidade e segurança. Ou seja, quando não se atinge o objetivo primário do teste de software, há chances maiores de o produto final não atender 100% daquilo que foi pedido, já que está mais suscetível a falhas.**  <font color=orange>Parcialmente correto. Nota 0,25</font>
2. (**1,0 ponto**) Explique o que é o teste exaustivo e porque sua execução não é possível. **Um teste exaustivo é um teste  que aborda todas as possibilidades possíveis de entrada, sem exceção. Um exemplo seria um teste para testar uma função soma() cuja entrada são dois números inteiros, retornando a soma destes dois números. Esse teste exaustivo deveria executar todas as possíveis combinações de números inteiros, logicamente se trata de uma modalidade de teste que é impraticável e impossível, já que abranger todas as combinações de entrada implica em um número estratosférico (infinito, neste caso) de combinações de entradas, que demandaria um enorme poder computacional e muito tempo para a realização do teste, tornando-o impossível.**
<font color=green>Certo</font>
3. (**1,0 ponto**) Cite pelo menos duas limitações da Técnica de Teste Funcional e duas da Técnica de Teste Estrutural. **Duas limitações do teste funcional são que ele depende de uma boa especificação de requisitos (algo que geralmente não é bem feito e, portanto, interfere na qualidade dos testes funcionais), além de que não é possível garantir que partes essenciais do software sejam executadas. Duas limitações do teste estrutural são que esse tipo de teste pode consumir tempo e recursos significativos para a aplicação, além de que caso o testador não tenha a habilidade necessária para compreender o fluxo de controle do programa, os testes estruturais podem ser comprometidos ou até mesmo inutilizados.**  <font color=green>Certo</font>
4. (**1,0 ponto**) Descreva pelo menos um dos quatro níveis de teste constantes da literatura especializada.  **Um dos quatro níveis de teste constantes da literatura especializada é teste unitário. O teste unitário é aquele teste que testa as pequenas porções de códigos, como métodos/funções ou uma classe de forma isolada, sem acessar nada fora de seu processo. Sendo assim, com os testes unitários conseguimos saber se as 'unidades de trabalho' (funções/componentes/classes/métodos etc) estão funcionando corretamente.** <font color=green>Certo</font>
5. (**1.0 ponto**)Descreva qual o propósito do critério de teste funcional Particionamento por Classes de Equivlência. **Seu propósito é de diminuir a quantidade de casos de testes no geral, mantendo uma boa cobertura do sistema de forma geral, validando os requisitos funcionais do sistema, procurando erros de interface, erros de desempenho, erro de possíveis acessos externos a bancos de dados por exemplo, erros de inicialização e término.** <font color=orange>Parcialmente correto, nota 0,3</font>
6. (**1.00 ponto**) Existe algum tipo de hierarquia em relação aos critérios de teste estrutural, todos os nós, todos os arcos e todos os caminhos? Se sim, explique-a, considerando a perspectiva dos níveis de cobertura desejados. **Existe uma hierarquia em relação aos critérios de teste estrutural, todos os nós, todos os arcos e todos os caminhos. Essa hierarquia depende do nível de cobertura desejado, ou seja, escolhe-se todos os caminhos caso se queira uma cobertura mais completa e detalhada da aplicação.** <font color=green>Certo</font>
7. Considere a especificação, a seguir, de um hipotético programa que objtiva a classificação de um triângulo, a partir dos valores informados para os seus três lados.

   a) Dado um triângulo cujos segmentos medem A, B e C, que são números inteiros positivos na faixa de 0 a 100. Esse triângulo somente existirá se: (A + B < C) ou (A + C < B) ou (B + C < A). **Consideraremos os sinais trocados para que a condição de existência do triângulo fique válida**
   b) Quanto às medidas dos seus lados o triângulo, poderá ser classicado em:
         • Isósceles = quando possui dois lados com a mesma medida;
         • Escaleno = quando todos os seus lados têm medidas diferentes;
         • Equilátero = quando todos os lados tem a mesma medida;
         • Acutângulo = quando o quadrado de um dos seus lados é menor que a soma do quadrado dois outros dois. (A<sup>2</sup> < B<sup>2</sup> + C<sup>2</sup>).
         • Retângulo: quando o quadrado de um dos seus lados é igual à soma do quadrado dois outros dois. (A<sup>2</sup> = B<sup>2</sup> + C<sup>2</sup>).
         • Obtusângulo: quando o quadrado de um dos seus lados é maior que a soma do quadrado dois outros dois. A<sup>2</sup> > B<sup>2</sup> + C<sup>2</sup>.

7.1 (**2.0 pontos**) Definir uma tabela de decisão para o teste tanto da existência do triângulo, quanto para a definição do seu tipo. Consulte exemplo de tabela de decisão na tarefa 005.

|-|(a+b)>c ou (a+c)>b ou (b+c)>a|N  | S  | S  | S  | S  | S| S  |S | S
|---|---|---|---|---|---|---|---|---|---|---|
|  | a = b  |-| N | N | N | N | S | S | S | S
|  | b = c  | | N  | N  |  S |  S |  N | N  | S | S
|  | c = a  |  - | N  | S  |  N |  S | N  | S  | N  | S
|  |Não é triangulo|  x |   |   |   |   |   |   |
|  |Equilatero|   |   |   |   |   |   |   |  |X
|  |Isoceles|   |   | X  |  X |   | X  |   |  |
|  |Escaleno|   | X  |   |   |   |   |   |  |

<font color=green>Certo</font>

7.2 (**2.0 pontos**) Criar os conjunto de casos de teste necessários para a cobertura das combinações constantes da tabela de decisão, seguindo o seguinte padrão:
|CT|Lado A|Lado B|Lado C|Resultado|
|---|---|---|---|---|
|  1 |  1 |  2 |  5 | Não é triângulo  |
|  2 |  6 |  8 |  10 | Escaleno  |
|  3 |  5 | 8  |  5 |  Isóceles|
|  4 |  8 | 5  |  5 |  Isóceles|
|  5 |  5 | 5  |  8 |  Isóceles|
|  5 |  6 | 6 |  6 |  Equilátero|

<font color=green>Certo</font>




INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega: Entregar este arquivo, editado com suas respostas, no formato .md, nominado da seguinte forma: ts2021-2_prova-p1_mat.md, onde mat deverá ser substituído pelo número da sua matrícula.
4. **Entrega diferente da especificada não será avaliada.**
5. Data da Entrega: 22/02/2022, as 23h59min.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
