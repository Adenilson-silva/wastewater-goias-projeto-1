# ANÁLISE TEMPORAL DA GESTÃO DE ESGOTOS EM GOIÁS (1992-2021) E PERSPECTIVAS FUTURAS (2022-2032)
<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1m56zgTpMRpCBBznDKY6OWnRWZqZmfm77" width="600">
</div>

## Contextualização do Projeto (cenário fictício desenvolvido pelo autor)

Atualmente, a questão do <a href="https://www.gov.br/ana/pt-br/assuntos/saneamento-basico/saneamento-basico-no-brasil/panorama-do-saneamento-no-brasil-1#:~:text=O%20saneamento%20b%C3%A1sico%20compreende%20os,manejo%20da%20%C3%A1gua%20das%20chuvas." target="_blank">Saneamento Básico</a> tornou-se uma das principais preocupações das prefeituras do estado de Goiás. O crescimento populacional, somado à urbanização acelerada, trouxe desafios para a infraestrutura de esgotamento sanitário, afetando diretamente a qualidade de vida da população.

Diante disso, em 2022, o governo estadual organizou um grande evento reunindo todos os prefeitos do estado e abrindo espaço para a participação popular. O objetivo era discutir os avanços, desafios e possíveis soluções para o saneamento básico em Goiás. Durante o evento, relatos negativos foram apresentados, dentre eles: municípios enfrentando despejo irregular de esgoto, rios contaminados, doenças de veiculação hídrica e uma clara desigualdade na distribuição dos serviços de saneamento entre os municípios.

A população exigia ações concretas, enquanto os prefeitos reconheciam as dificuldades na obtenção de diagnósticos precisos para embasar políticas públicas eficazes. Ficou evidente que a falta de informações organizadas e atualizadas sobre o esgotamento sanitário impedia a criação de estratégias eficientes para solucionar o problema.

Ao final do evento, o governo estadual decidiu que seria necessário produzir um estudo geral para oferecer um panorama realista da situação do esgotamento sanitário em Goiás. Coube à Secretaria de Meio Ambiente a responsabilidade por conduzir essa iniciativa, contando com a colaboração das prefeituras para fornecer informações detalhadas sempre que necessário. O prazo estabelecido para o desenvolvimento do estudo seria de 60 (sessenta) dias.

#### Definição das responsabilidades
Ao tomar ciência da solicitação do governador, o secretário estadual de meio ambiente decidiu utilizar a  <a href="https://www.gov.br/transportes/pt-br/assuntos/portal-da-estrategia/artigos-gestao-estrategica/como-implementar-a-matriz-raci" target="_blank">Matriz RACI</a> para organizar a gestão de elaboração do estudo, definindo assim os papéis e responsabilidades das partes envolvidas. A seguir, é apresentada a matriz de inicio do projeto:
| Etapa  | Diagnóstico geral da situação do esgotamento sanitário em Goiás |
|-----------|-----------------------------------------------------------------------------------|
| **_Responsible_** | Será criado um Grupo de Trabalho (GT) composto por dois (2) analistas ambientais da Secretaria de Meio Ambiente do Estado, responsáveis pelo desenvolvimento do estudo. Este estudo utilizará como subsídio o projeto elaborado por uma empresa contratada por meio de licitação, especializada em consultoria de ciência de dados. A empresa será encarregada de estruturar e desenvolver um projeto que empregue técnicas de análise e modelagem de dados, com o intuito de embasar o estudo solicitado. O objetivo principal é transformar os dados coletados em informações concretas, que auxiliem na formulação de políticas públicas mais eficientes. |
| **_Accountable_**  | Secretário de Meio Ambiente do Estado de Goiás. |
| **_Consulted_** | Considerando a urgência na elaboração do estudo, os demais analistas ambientais da Secretaria poderão ser consultados para apoiar as atividades em desenvolvimento. Além disso, as secretarias municipais de Meio Ambiente estarão à disposição para colaborar no suporte e na execução do estudo. |
| **_Informed_**  | Governador, prefeitos e a população do estado de Goiás. |


#### Definição do fluxo de trabalho
Após definir as responsabilidades dos envolvidos, o secretario, juntamente com os analistas responsáveis pela elaboração do estudo, definiram o fluxo de trabalho por meio do <a href="https://medium.com/@gelsonm/pace-framework-a-beginners-guide-to-structured-ml-projects-7089b6001615" target="_blank">Método PACE</a>. A seguir, é apresentada a matriz:
| Etapa        | Descrição | Responsável | Prazo | Ações/Observações |
|--------------|-----------|-------------|-------|-------------------|
| **_Plan_**     | Planejamento e definição de metas e objetivos. Coleta dos dados. | Analistas Ambientais e empresa de consultoria. | 5 dias | - |
| **_Analyse_**       | Processamento e tratamento dos dados. Análise exploratória dos dados | Empresa de consultoria. | 15 dias | Durante esta etapa, poderá ser necessário a solicitação de esclarecimentos pela empresa de consultoria. |
| **_Construct_**    | Construção do modelo de _Machine Learning_. | Empresa de consultoria. | 30 dias | - |
| **_Execute_**      | Entrega dos resultados. | Analistas ambientais e empresa de consultoria. | 10 dias | Nesta etapa, os analistas ambientais deverão coletar o projeto entregue pela a empresa de consultoria e estruturar o estudo] |

#### Definição do problema e do objetivos
Durante as reuniões de planejamento entre os analistas ambientais e a empresa de consultoria, ficou estabelecido que, para garantir uma compreensão clara e objetiva do projeto, seria utilizada a técnica [5W-S](https://www.esalq.usp.br/qualidade/ferramentas/5w1h.htm). Essa abordagem permitiria estruturar a descrição do problema de forma detalhada. A seguir, é apresentada a aplicação da técnica e os objetivos, respectivamente.
| **Pergunta**           | **Descrição**                                                                                                                                                                                                                       |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Quem? (_Who?_)**      | Os dados utilizados neste projeto serão coletados de 3 fontes distintas: <br> 1 – Sistema Nacional de Informações sobre o Saneamento (SNIS) <br> 2 – Instituto Brasileiro de Geografia e Estatística (IBGE)<br> 3 – Instituto Mauro Borges de Estatísticas e Estudos Socioeconômicos (IMB) |
| **O quê? (_What?_)**    | Este projeto realizará a análise descritiva e preditiva dos dados relativos ao volume de esgoto produzido, volume de esgoto tratado e volume de esgoto tratado em todos os 246 municípios do estado de Goiás.                    |
| **Por quê? (_Why?_)**   | Dada a importância do assunto “saneamento básico”, este projeto motiva-se pela necessidade de verificar a efetividade das políticas públicas de tratamento de esgotos que estão sendo desenvolvidas no estado de Goiás.            |
| **Onde? (_Where?_)**    | Este projeto tratará especificamente do estado de Goiás e seus municípios.                                                                                                                                                         |
| **Quando? (_When?_)**   | Os dados utilizados neste projeto contemplarão a seguinte faixa de tempo: <br> • Análise Descritiva: do ano 1992 ao ano 2021; <br> • Análise Preditiva: do ano 2022 ao ano 2032.                                                 |

**Objetivos**
- Coletar e tratar dados relativos aos volumes de esgotos produzidos, coletados e tra-tados nos munícipios do estado de Goiás;
- Descrever os dados coletados, a fim de averiguar possíveis comportamentos e/ou tendências entre o período de 1992 a 2021;
- Prever comportamentos e/ou tendências futuras (para o período compreendido en-tre 2022 e 2032); e
- Constatar se, por meio de modelos preditivos, é possível inferir se a atual ação do poder público no estado de Goiás garantirá ou não a melhoria dos serviços de coleta e tratamento na região.


## Tecnologias utilizadas
- Python
- Trello


## Quem é o Autor?
Leia meu resumo e me envie uma mensagem: https://www.linkedin.com/in/adenilson-silva/
