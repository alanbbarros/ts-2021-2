<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P2 - 12/04/2022</p>

Matrícula: 201802751

Nome: Alan Brito Barros

<p><font color="red">Nota 4,8</font></p>


1. Quanto ao Processo de Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Defina os seguintes conceitos Processo de Teste de Software, Projeto de Teste de Software e Plano de Teste de Sofware. **O processo de teste de software pode ser definido como o conjunto de etapas, atividades e fases que engloba tudo o que é necessário para que se teste um software. Desde a iniciação e o planejamento, passando pela elaboração de um plano de testes, até o momento da execução e encerramento dos testes com a entrega de um relatório de testes. O plano de testes estabelece várias métricas como marcos do processo, alocação de recursos, cronograma de atividades, ferramentas e etc. O projeto de teste estabelece os métodos de teste juntamente com cenários e casos de teste**
      <p><font color="red">Nota 0,5</font></p>

   2. (**0,5 ponto**) Descreva o relacionamento existente entre estes conceitos. **A relação existente entre os conceitos é de que o processo de teste de software é o que abrange tudo, envolve todas as fases e o todo é chamado justamente de um processo de teste de software. O plano de teste e o projeto de teste por sua vez são artefatos que são produzidos dentro de um processo de teste de software, sendo que o artefato de saída (o resultado) da fase de iniciação de um processo de teste de software é justamente o plano de testes, enquanto que o projeto de teste tem suas primeiras especificações preliminares feitas na fase de planejamento, que é também uma das fases do processo de teste de software, assim como a fase de iniciação.**
      <p><font color="red">Nota 0,3</font></p>

2. (**1,0 pontos**) Descreva as vantagens para a equipe de desenvolvimento ao se adotar um processo de teste ágil. **Uma equipe de desenvolvimento, ao adotar um processo de teste ágil, busca um processo que tenha um planejamento menos engessado e mais iterativo e incremental, permitindo à equipe uma melhor resposta à mudanças, promovendo muitas vezes uma maior produtividade. Além disso, os testes ágeis seguem o mesmo princípio, com ciclos frequentes, o que aumenta a carga de feedback que o time de desenvolvimento recebe e, somado ao fato de que todos os membros do time realizam os testes, resulta em uma maior integração do time e do entendimento do time sobre o produto que está sendo desenvolvimento como um todo, favorecendo também a produtividade e a qualidade do produto final. Um último ponto que pode ser ressaltado é que, de forma geral, os testes ágeis tendem a dar uma ênfase nos testes automatizados em detrimento dos testes manuais, o que também é uma vantagem para a equipe de desenvolvimento que adota um processo de teste ágil.**
<p><font color="red">Nota 1,0</font></p>

3. (**1,0 ponto**) Cite pelo menos três características do Teste Exploratório. **Uma característica do teste exploratório é de que ele existe em um ambiente onde os script ou são removidos ou são menos rígidos. Com isso, o teste exploratório promove uma maior liberdade para o testador interagir com a aplicação da forma que deseja, sem muitas amarras. Outra característica é que os resultados do teste são gerados a medida que os testes são realizados, ou seja, os casos de teste, documentação, capturas de tela e demais relatórios são feitos conforme os testes são realizados já que não há previamente nada estabelecido sobre qual curso testes exploratórios deverão tomar. Outra característica do teste exploratório é que ele possui duas diretrizes principais: o teste exploratório de escopo reduzido e o teste exploratório de escopo abrangente.**
<p><font color="red">Nota 1,0</font></p>

4. Considere os arquivos .java (Banco.java, Agencia.java, Conta.java e BankValidator.java). Nos próprios arquivos .java estão definidas as regras para cadastramento de cada um deles (Banco, Agencia e Conta). Desta forma, pede-se:
   1. (2.0 Pontos) Definir os cenários de teste suficientes para testar o cadastro e movimentações financeiras envolvendo bancos, agências e contas, conforme especificado. Para cada cenário definir os critérios de teste adequados à definição dos seus casos de teste.

**Cenários de teste para Banco**
|  Cenário  |           Descrição do cenário        | Válido ou Inválido |
|--|----|---|
| CE01 | numero com 3 digitos                        | Válido |
| CE02 | numero abaixo de 3 digitos                    | Inválido |
| CE03 | numero acima de 3 digitos                    | Inválido |
| CE04 | nome com tamanho < 5 caracteres             | Inválido |
| CE05 | nome com tamanho > 100                       | Inválido |
| CE06 | nome com tamanho > 5 && tamanho <= 100| Válido |
| CE07 | numero com caracteres não numericos                      | Inválido |


**Cenários de teste para Agencia**
|  Cenário  |           Descrição                          | Válido ou Inválido |
|--|----|---|
| CE01 | numero abaixo de 3 digitos                   | Inválido |
| CE02 | numero com 3 digitos                          | Válido |
| CE03 | numero com 4 digitos                          | Válido |
| CE04 | numero com 5 digitos                          | Válido |
| CE05 | numero acima de 5 digitos                     | Inválido |
| CE06 | nome com tamanho < 5 caracteres             | Inválido |
| CE07 | nome com tamanho > 100                       | Inválido |
| CE08 | nome com tamanho > 5 && tamanho <= 100| Válido |
| CE09 | cidade abaixo de 5 caracteres                        | Inválido |
| CE10 | cidade de 5 a 100 caracteres                 | Válido |
| CE11 | cidade acima 100 caracteres                      | Inválido |
| CE12 | numero com caracteres não numericos                      | Inválido |


**Cenários de teste para Conta**
|  ID  |           Descrição                          |Válido ou Inválido |
|--|----|---|
| CE01 | numero com 6 digitos                           | Válido |
| CE02 | numero menor que 6 dígitos                          | Inválido |
| CE02 | numero maior que 6 dígitos                          | Inválido |
| CE03 | numero com caractere não númerico            | Inválido |
| CE04 | nome do tipo = cheque          | Válido |
| CE05 | nome do tipo = poupança          | Válido |
| CE06 | nome do tipo != cheque          | Inválido |
| CE07 | nome do tipo != poupança          | Inválido |
| CE08 | nome do tipo = Cheque com limite = cheque especial    | Válido |
| CE09 | nome do tipo = Cheque com limite != cheque especial   | Inválido |
| CE10 | nome do tipo != Poupança com limite = cheque especial |Inválido |

<p><font color="red">Nota 1,0</font></p>

   2. (2.0) Definir os casos de teste suficientes para a cobertura do teste de cada um dos cenários definidos. Documentar os casos de teste no seguinte padrão:

**Casos de teste bloco de cenários Banco**
   | CT | Valores de Entrada | Resultado esperado |
   |---|---|---|
   | CT01 | 234 | OK |
   | CT02 | 24 | Invalid |
   | CT03 | 3892 | Invalid |
   | CT04 | 'aaa' | Invalid |
   | CT05 | 'a...'(length > 100) | Invalid |
   | CT06 | 'aaaaaaa' | OK |
   | CT07 | a23 | Invalid |

**Casos de teste bloco de cenários Agencia**
   | CT | Valores de Entrada | Resultado esperado |
   |---|---|---|
   | CT01 | 24 | Invalid |
   | CT02 | 244 | OK |
   | CT03 | 3892 | OK |
   | CT04 | 38923 | OK |
   | CT05 | 123456 | Invalid |
   | CT06 | 'aa' | Invalid |
   | CT07 | 'a...'(150x) | Invalid |
   | CT08 | 'aaaaaaa' | OK |
   | CT09 | 'gyn' | Invalid |
   | CT10 | 'goiania' | OK |
   | CT11 | 'goianiaa...'(length > 100) | Invalid |
   | CT12 | a23 | Invalid |

   **Casos de teste bloco de cenários Conta**
   | CT | Valores de Entrada | Resultado esperado |
   |---|---|---|
   | CT01 | 123456 | OK |
   | CT02 | 244 | Invalid |
   | CT03 | 12345678 | Invalid |
   | CT04 | tipo = 'cheque' | OK |
   | CT05 | tipo = 'poupanca' | OK |
   | CT06 | tipo = 'conta corrente' | Invalid |
   | CT07 | tipo = 'cartao de credito' | Invalid |
   | CT08 | tipo = 'cheque com limite', limite = cheque especial| OK |
   | CT09 | tipo = 'cheque com limite', limite = 0 | Invalid |
   | CT09 | tipo = 'conta corrente', limite = cheque especial | Invalid |

<p><font color="red">Nota 1,0</font></p>

   3. (3.0 Pontos) Implementar (na linguagem de programação java) as classes para o teste da criação dos objetos e das movimentações financeiras envolvendo bancos e agências e contas.
<p><font color="red">Nota 0,0</font></p>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing.
3. Forma de Entrega: arquivo compactado contendo:
   1. Este arquivo md, respondido.
   2. Classes de teste para (BancoTest, AgenciaTest e ContaTest);
   3. O arquivo compactado deverá ter o seguinte nome prova_p2<mat>.zip, onde mat é o número da matrícula do aluno(a).
5. Data da Entrega: 12/04/2022, as 22hs.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
7. Obs: segue no mesmo pacote o arquivo "org.apache.commons.lang.StringUtils", que é uma dependência do projeto. É deve ser inserida no _classpath_ do projeto de implementação da questão 4, caso não esteja utilizando o _maven_.
