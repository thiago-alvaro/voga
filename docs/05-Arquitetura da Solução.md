# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

![Arquitetura da Solução](img/02-mob-arch.png)

## Diagrama de Classes

O diagrama de classes ilustra graficamente como será a estrutura do software, e como cada uma das classes da sua estrutura estarão interligadas. Essas classes servem de modelo para materializar os objetos que executarão na memória.

<p align="center">
    <img src="img/Arquitetura-Solucao-Classe.jpg">
</p>

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Classes”.

> - [Diagramas de Classes - Documentação da IBM](https://www.ibm.com/docs/pt-br/rational-soft-arch/9.6.1?topic=diagrams-class)
> - [O que é um diagrama de classe UML? | Lucidchart](https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-classe-uml)

## Modelo ER

O Modelo ER representa através de um diagrama como as entidades (coisas, objetos) se relacionam entre si na aplicação interativa.]

<p align="center">
    <img src="img/Arquitetura-Solucao-ER.jpg">
</p>

As referências abaixo irão auxiliá-lo na geração do artefato “Modelo ER”.

> - [Como fazer um diagrama entidade relacionamento | Lucidchart](https://www.lucidchart.com/pages/pt/como-fazer-um-diagrama-entidade-relacionamento)

## Esquema Relacional

O Esquema Relacional corresponde à representação dos dados em tabelas juntamente com as restrições de integridade e chave primária.

<p align="center">
    <img src="img/Arquitetura-Solucao-Esquema-Relacional.jpg">
</p>
 
As referências abaixo irão auxiliá-lo na geração do artefato “Esquema Relacional”.

> - [Criando um modelo relacional - Documentação da IBM](https://www.ibm.com/docs/pt-br/cognos-analytics/10.2.2?topic=designer-creating-relational-model)

## Modelo Físico

Entregar um arquivo banco.sql contendo os scripts de criação das tabelas do banco de dados. Este arquivo deverá ser incluído dentro da pasta src\bd.

## Tecnologias Utilizadas

### [React Native]
React Native é uma biblioteca Javascript criada pelo Facebook. É usada para desenvolver aplicativos para os sistemas Android e iOS de forma nativa.

### [SQLite]
SQLite é uma biblioteca em linguagem C que implementa um banco de dados SQL embutido. Programas que usam a biblioteca SQLite podem ter acesso a banco de dados SQL sem executar um processo SGBD separado.

### [Node.js]
Node.js é um software de código aberto, multiplataforma, baseado no interpretador V8 do Google e que permite a execução de códigos JavaScript fora de um navegador web.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.

## Hospedagem

O aplicativo será hospedado na plataforma Heroku.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)

## Qualidade de Software

|**Característica **            |**Subcaracterísticas**|**Pergunta chave para subcaracterísticas**|
|-------------------------------|-----------------------|------------------------------------------|
|*Funcionalidade*                            |Adequação          |Propõe-se a fazer o que é apropriado? |
|                                           |Acurácia           | Faz o que foi proposto de forma correta?|
|                                           |Interoperabilidade | Interage com os sistemas especificados?|
|                                           |Conformidade       | Está de acordo com as normas, leis e etc.?|
|                                           |Segurança          | de acesso Evita o acesso não autorizado aos dados?|
|                                           |Acurácia           | Faz o que foi proposto de forma correta?|
|-------------------------------|-----------------------|------------------------------------------|
|*Confiabilidade*                           |Maturidade             |Com que freqüência apresenta falhas?|
|                                           |Tolerância a falhas    |Ocorrendo falhas, como ele reage?|
|                                           |Recuperabilidade       |É capaz de recuperar dados em caso de falha?|
|-------------------------------|-----------------------|------------------------------------------|
|*Usabilidade*                              |Inteligibilidade             |É fácil entender o conceito e a aplicação?|
|                                           |Apreensibilidade             |É fácil aprender a usar?|
|                                           |Operacionalidade             |É fácil de operar e controlar?|
|-------------------------------|-----------------------|------------------------------------------|
|*Eficiência*                                |Tempo             |Qual é o tempo de resposta, a velocidade de execução?|
|                                            |Recursos          |Quanto recurso usa? Durante quanto tempo?|
|-------------------------------|-----------------------|------------------------------------------|
|*Manutenibilidade*                         |Analisabilidade          |É fácil de encontrar uma falha, quando ocorre?|
|                                           |Modificabilidade         |É fácil modificar e adaptar?|
|                                           |Estabilidade             |Há grande risco quando se fazem alterações?|
|                                           |Testabilidade            |É fácil testar quando se fizer alterações?|
|-------------------------------|-----------------------|------------------------------------------|
|*Portabilidade*                         |Adaptabilidade                   |É fácil adaptar a outros ambientes?|
|                                        |Capacidade para ser instalado    |É fácil instalar em outros ambientes?|
|                                        |Conformidade                     |Está de acordo com padrões de portabilidade?|
|                                        |Capacidade para substituir       |É fácil usar para substituir outro?|






Conceituar qualidade de fato é uma tarefa complexa, mas ela pode ser vista como um método gerencial que através de procedimentos disseminados por toda a organização, busca garantir um produto final que satisfaça às expectativas dos stakeholders.

No contexto de desenvolvimento de software, qualidade pode ser entendida como um conjunto de características a serem satisfeitas, de modo que o produto de software atenda às necessidades de seus usuários. Entretanto, tal nível de satisfação nem sempre é alcançado de forma espontânea, devendo ser continuamente construído. Assim, a qualidade do produto depende fortemente do seu respectivo processo de desenvolvimento.

A norma internacional ISO/IEC 25010, que é uma atualização da ISO/IEC 9126, define oito características e 30 subcaracterísticas de qualidade para produtos de software.
Com base nessas características e nas respectivas sub-características, identifique as sub-características que sua equipe utilizará como base para nortear o desenvolvimento do projeto de software considerando-se alguns aspectos simples de qualidade. Justifique as subcaracterísticas escolhidas pelo time e elenque as métricas que permitirão a equipe avaliar os objetos de interesse.

> **Links Úteis**:
>
> - [ISO/IEC 25010:2011 - Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE) — System and software quality models](https://www.iso.org/standard/35733.html/)
> - [Análise sobre a ISO 9126 – NBR 13596](https://www.tiespecialistas.com.br/analise-sobre-iso-9126-nbr-13596/)
> - [Qualidade de Software - Engenharia de Software 29](https://www.devmedia.com.br/qualidade-de-software-engenharia-de-software-29/18209/)
