# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Enumere quais cenários de testes foram selecionados para teste. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.

## Ferramentas de Testes (Opcional)

Comente sobre as ferramentas de testes utilizadas.

> **Links Úteis**:
>
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> - [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)


**Plano de teste dos requisitos RF-7 e RF-8**

**Requisito:** RF-7: O site deve conter informações de manuseio e conservação de alimentos.

**História/Contexto:** *Eu como* Maria de Fátima *desejo* saber como escolher e conservar os melhores alimentos disponíveis no mercado *para* evitar desperdícios.

*Eu como* Maria José **desejo* saber como armazenar os alimentos que compro *para* não estragarem antes de serem usados.  

**Caso de teste 1:**
**Objetivo:** Testar a funcionalidade.
**Execução:** Entrar na home. Selecionar alimento em carrossel. 
**Saída esperada:** A página de informações nutricionais onde contém informações sobre armazenamento e manuseio de determinado alimento.  
**Saída real do sistema:** Página de informações nutricionais onde contém informações sobre armazenamento e manuseio de determinado alimento.  

![image](../docs/imagens2/planoTesteRF7Caso1Part1.png
![image](../docs/imagens2/planoTesteRF7Caso1Part2.png


**Caso de teste 2:**
**Objetivo:** Testar a funcionalidade.
**Execução:** Entrar na aba de receitas. Clicar para saber mais informações nutricionais. 
**Saída esperada:** A página de informações nutricionais onde contém informações sobre armazenamento e manuseio de determinado alimento.  
**Saída real do sistema:** Página de informações nutricionais onde contém informações sobre armazenamento e manuseio de determinado alimento.  

![image](../docs/imagens2/planoTesteRF7Caso2Part1.png
![image](../docs/imagens2/planoTesteRF7Caso2Part2.png


**Caso de teste 3:**
**Objetivo:** Testar a funcionalidade.
**Execução:** Entrar na aba de alimentos. Clicar em um dos alimentos apresentados. 
**Saída esperada:** A página de informações nutricionais onde contém informações sobre armazenamento e manuseio de determinado alimento.  
**Saída real do sistema:** Página de informações nutricionais onde contém informações sobre armazenamento e manuseio de determinado alimento.  

![image](../docs/imagens2/planoTesteRF7Caso3Part1.png
![image](../docs/imagens2/planoTesteRF7Caso3Part2.png


**Caso de teste 4:**
**Objetivo:** Testar a funcionalidade.
**Execução:** Selecionar uma receita. Clicar para saber mais informações sobre o alimento principal da receita.  
**Saída esperada:** A página de informações nutricionais onde contém informações sobre armazenamento e manuseio de determinado alimento.  
**Saída real do sistema:** Página de informações nutricionais onde contém informações sobre armazenamento e manuseio de determinado alimento.  

![image](../docs/imagens2/planoTesteRF7Caso4Part1.png
![image](../docs/imagens2/planoTesteRF7Caso4Part2.png



**Requisito:** RF-8: O site deve conter seção de receitas.

**História/Contexto:** *Eu como* Bruna Santos *desejo* aprender receitas de qualidade e com baixo custo *para* economizar sem prejudicar a dieta da família.

*Eu como* Maria José *desejo* aprender receitas novas *para* fazer um cardápio saudável para minha família. 


**Caso de teste 1:**
**Objetivo:** Testar a funcionalidade.
**Execução:** Selecionar a aba de receitas. Selecionar uma receita.
**Saída esperada:** Carregar a página com todas receitas disponíveis no site e após seleção de uma receita especifica a amostragem de tal receita.
**Saída real do sistema:** Carregar a página com todas receitas disponíveis no site e após seleção de uma receita especifica a amostragem de tal receita.

![image](../docs/imagens2/planoTesteRF8Caso1Part1.png
![image](../docs/imagens2/planoTesteRF8Caso1Part2.png


**Caso de teste 2:**
**Objetivo:** Testar a funcionalidade.
**Execução:** Selecionar uma receita específica que está disponível na home. 
**Saída esperada:** A página da receita selecionada.
**Saída real do sistema:** A página da receita selecionada.

![image](../docs/imagens2/planoTesteRF8Caso2Part1.png
![image](../docs/imagens2/planoTesteRF8Caso2Part2.png


**Caso de teste 3:**
**Objetivo:** Testar a funcionalidade.
**Execução:** Na aba de informações nutricionais de um alimento selecionado clicar em receita.
**Saída esperada:** A página da receita selecionada.
**Saída real do sistema:** A página da receita selecionada.

![image](../docs/imagens2/planoTesteRF8Caso3Part1.png
![image](../docs/imagens2/planoTesteRF8Caso3Part2.png


