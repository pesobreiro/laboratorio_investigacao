# Laboratório de Investigação

Investigar consiste em identificar problemas, colocar questões, refletir, admitir erros, aprender novas coisas e tentar encontrar soluções utilizando um método científico, o que pode ser recompensador:

![Job Offer](./img/oferta.jpg)

Documentação e recursos para a disciplina de Laboratório de Investigação. Como é que podemos abordar o problema, onde se procura responder a questões como:
* Como é que podemos fazer uma revisão de literatura? 
* Como é que podemos fazer uma pesquisa bibliográfica? 
* Quais são as ferramentas que podemos utilizar?
* Como é que podemos utilizar ASReview para a seleção de artigos? 
* Como é que podemos utilizar o Zotero para a gestão de referências bibliográficas?
* Como é que podemos utilizar a inteligência artificial para apoiar a investigação?

# Workflow para a elaboração de um plano de investigação
* Qual é o problema subjacente à investigação do estudo ou projeto? 
  * Formular uma questão de investigação
  * Depois de formular a questão de investigação, podemos definir sub-questões, e.g. Questão qual é o impacto da pandemia COVID-19 no ensino à distância? Sub-questões: Quais são as vantagens e desvantagens do ensino à distância? Quais são as ferramentas tecnológicas mais utilizadas no ensino à distância? Quais são as competências necessárias para o ensino à distância?
  * Explicar sucintamente cada uma das sub-questões, frase curtas, 1 ou 2 linhas
* Utilizar o PICOC (Population, Intervention, Comparison, Outcome, Context) como base para a criar a 'string' de pesquisa:
* Exemplificar uma questão de investigação e sub-questões a partir de um problema dos alunos
* Ferramentas que podemos utilizar para fazer uma revisão de literatura:
  * Exemplificar com um problema dos alunos como se faz uma revisão de literatura
  * Utilização do [Parsifal](https://parsif.al/about/) para ajudar nos objectivos, PICOC, questões de pesquisa, search string, keywords e sinónimos, seleção das fontes, critérios de inclusão e exclusão, bem como os mecanimos necessários para construir uma checklist para uma checklist para uma avaliação qualitativa e formulários extração de dados.
  * Um ficheiro Excel para a avaliação qualitativa das questões de investigação
  * Como importar os artigos selecionados para o zotero.... TODO...
  * Utilização do Zotero para a gestão de referências bibliográficas
* Pesquisar em bases de dados científicas
  * Scopus (Bom mas é pago e não é acessível a todos)
  * IEEE Digital Library (Conseguimos pesquisar)
  * SpringerLink (Conseguimos pesquisar)
  * Science@Direct (Conseguimos pesquisar)
* Exemplificar com um problema dos alunos como se faz uma pesquisa bibliográfica
* Utilização do ASReview para a seleção de artigos
  * Instalação	e exemplo de utilização do [ASReview](https://asreview.readthedocs.io/en/latest/index.html) 
    * Com conda: `conda install -c conda-forge asreview`
    * Com pip: `pip install asreview`
    * Com docker: `docker run -it asreview/asreview:latest`
  * Importação das referências selecionadas do ASReview para o Zotero
* Utilização do Zotero para a gestão de referências bibliográficas

# Bases de dados

* [ACM Digital Library](http://portal.acm.org)
* [IEEE Digital Library](http://ieeexplore.ieee.org)
* [ISI Web of Science](http://www.isiknowledge.com)
* [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/)
* [Science@Direct](http://www.sciencedirect.comg
g [Scopus](http://www.scopus.com)
* [Springer Link](http://link.springer.com)

# Ferramentas apoio

* [ResearchKit](https://www.researchkick.com/start)
* [Scribbr](https://www.scribbr.com/plagiarism-checker/)
* Bibliometrix
* AI powered literature review and tools for researchers:
  * Revisão de literatura:
    * [Perplexity](https://perplexity.ai/):  Answering questions in a comprehensive and informative way, similar to a search engine but with more conversational abilities
    * [Elicit](https://elicit.com/): Research assistant that uses language models to automate research tasks, such as finding relevant papers, summarizing papers, and answering questions
    * [Sematicscholar](https://www.semanticscholar.org/)
    * [Anysummary](https://www.anysummary.app/)
    * [ChatPDF](https://chatpdf.com/)
  * Definição de hipóteses:
    * Utilização da inteligência artificial generativa para GPT3/4 a partir de uma prompt 

A Prompt mágica

```
You are an expert computer science. Your research interests are in Predictive Analytics, 
Machine Learning, and Data Mining. You are interested in generating hypotheses in the field of 
Computer Science and Artificial Intelligence.
Your task is to generate counterintuitive yet plausible hypotheses. They should
combine different sub fields of Computer Science and advance theoretical knowledge.
They should not be incremental.
Make sure that your hypotheses are precisely stated and incorporate a comparison
group. Begin each hypothesis with "Hypothesize that" and generate 100 hypotheses.
```


# Documentos de apoio

* Etapas gerais para revisão de literatura [aqui](./docs/01.revisao_literatura.pdf)
* Utilização do [Zotero](./docs/02.zotero_Ferramentas.pdf)
* Instalação [Docker](./docs/03.instalacao_docker.pdf), mais simples é mesmo com Anaconda para ASReview


# Exemplo 

## Caso 1

Problema de estudo: Utilização de drones para prever a evolução de um incêndio através da inteligência Artificial

Baseado neste problema de investigação foram formuladas as seguintes questões: 

* RQ1: Qual é o estado da arte da investigação que está a ser desenvolvida?
* RQ2: Quais são os algoritmos que são utilizados para prever a evolução do incêndio?
* RQ3: Quais são as variáveis normalmente utilizadas para perceber a evolução dos incêndios?

The authors used the Petticrew and Roberts (CITACAO) Population, Intervention, Comparison, Outcome and Context (PICOC).

* Population: Estudos que abordem utilização de drones para prever incêndios
* Intervention: Algoritmos de Machine Learning para prever evolução dos incêndios
* Comparison: Diferentes tipos de algoritmos para prever os incêndios
* Outcome: Resumo das questões de pesquisa, algoritmos utilizados e lacunas existentes na investigação
* Context: Academia

Baseado no PICOC seguindo a abordagem recomendada por Kitchmen e Charters (REF) o critério de pesquisa foi, por 
exemplo:

`(wildfire) AND (drones) AND ("machine Learning" OR prediction OR "Deep Learning" OR "Predictive Analytics")`

A partir da keywords de pesquisa, vamos procurar nas base de dados: SpringerLink, Science@Direct, 
IEEE Digital Library, and ACM Digital Library

Onde realizam a pesquisa no title, abstract, and keywords identificando um intervalo de pesquisa January 2010 and 2024 (Outubro),
definindo os critérios de exclusão (Livros, patentes, teses de mestrado e artigos que não estão em inglês).

Convém fazer uma contextualização em relação a problema, nomeadamente para perceber como é que se está a investigar, tipo
de terminologia utilizada, por exemplo para perceber que estudos estão a ser feitos para "afinar" as questões de pesquisa e 
termos a utilizar na string de pesquisa e fazer a introdução à revisão de literatura.
Ver exemplo [aqui](https://elicit.com/notebook/6b00c2c5-a34a-4df3-94ee-3db1663e53a5). Depois podem interagir com os PDFs dos artigos e pedirem para resumir as ideias principais, utilizando por exemplo ChatPDF ou analisando com mais detalhe lendo com 
algum cuidado os artigos.
Outro aspeto importante é perceber se existem revisões de literatura similares ao que estão a fazer e não fazer o mesmo. Caso
existam, tentar alterar o âmbito ou o problema de estudo para diferenciar.

# Bibliografia

Biggam, J. (2021). Succeeding with Your Master’s Dissertation: A Step-by-Step Handbook. McGraw-Hill Education.
Dawson, C. (2019). Introduction to Research Methods 5th Edition: A Practical Guide for Anyone Undertaking a Research Project. Robinson
Press.
