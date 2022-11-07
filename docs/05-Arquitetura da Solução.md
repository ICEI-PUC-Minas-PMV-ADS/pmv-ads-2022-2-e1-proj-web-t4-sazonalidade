# Arquitetura da Solução

Nesta seção são apresentados os detalhes técnicos da solução criada pela equipe, tratando
dos componentes que fazem parte da solução e do ambiente de hospedagem da solução.

## Diagrama de componentes

Os componentes que fazem parte da solução são apresentados nas figuras que se segue.

Exemplo:

Os componentes que fazem parte da solução são apresentados nas abaixo:

![image](https://user-images.githubusercontent.com/114542015/194774283-5dac5e64-1a6c-4385-b668-9ed8d7e9e517.png)
![image](https://user-images.githubusercontent.com/114542015/194774293-8f22f626-35d7-40dc-a36e-2a7499a95ae4.png)

Link de acesso para visualização interativa: https://app.diagrams.net/#G1quexPNw6O9oC4Z5n7OYCdcjto-8aWsJs

A solução implementada conta com os seguintes módulos:

- **Contexto** - Mostra as interações de forma macro sem muitos detalhes entre usuários e sistemas que fazem parte do software.
  - **Site(Sazoqualidade)** - É aquele que mostra as informações de forma simples e interativa para o usuário.
  - **Site Externo (Ceasa)** - É aquele que fornece as informações para o site Sazoqualidade.
  - **Contêiner** - Mostra de forma mais detalhada que o contexto, no entanto ainda superficial.
    - **Aplicação Web** - conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
    - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles:
      - **Receitas salvas** - seções de receitas salvas
      - **Preferidas** - lista de seções de favoritas mantidas para leitura e acesso posterior
  - **Sistema Externo (Hospedagem)** - local na Internet onde as páginas são mantidas e acessadas pelo navegador.

## Tecnologias Utilizadas

## Hospedagem
