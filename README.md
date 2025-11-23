<img width="1300" height="240" alt="image" src="https://github.com/user-attachments/assets/7be1261c-228e-4f50-9257-df0f0a3239ea" />

<br />

<span id="denarius-data">

# <p align="center">Denarius Data</p>
<p align="center">
    <a href="#desafio">Desafio</a>  |  
    <a href="#solucao">Solução</a>  |   
    <a href="#backlog-do-produto">Backlog do Produto</a>  |  
    <a href="#dor">DoR</a>  |  
    <a href="#dor">DoD</a>  |  
    <a href="#cronograma-de-sprints">Cronograma de Sprints</a>  |  
    <a href="#tecnologias">Tecnologias</a> | 
    <a href="#manual-de-instalacao">Manual de Instalação</a> | 
    <a href="#manual-do-usuario">Manual do Usuário</a> | 
    <a href="#documentacao-api">Documentação API</a> | 
    <a href="#modelagem-de-banco-de-dados">Modelagem de Banco de Dados</a> | 
    <a href="#equipe">Equipe</a>
</p>

> Status do Projeto: Finalizado ✅ <br /><br />
> Pasta de Documentação: [Link](https://github.com/DenariusData/API-4SEM/tree/main/docs) 📄 <br /><br />
> Vídeo do Projeto: [A ser feito]() 📽️

<span id="desafio">

## 🏅 Desafio

Diante da necessidade de aprimorar a gestão do tráfego urbano em São José dos Campos, o desafio consiste em implementar uma solução proativa de monitoramento e resposta a incidentes. A cidade carece de um sistema integrado que permita a tranformação de dados dos radares em insights acionáveis, a definição de indicadores específicos para disparo de alertas e a eficiente alocação de agentes de mobilidade para as áreas e situações mais críticas, otimizando assim os recursos e melhorando a fluidez do trânsito.

<span id="solucao">

## 🏅 Solução

Foi desenvolvido um Sistema Inteligente de Monitoramento e Alerta de Tráfego. Esta solução centraliza o controle do trânsito por meio dos radares, permitindo o cadastro de indicadores e níveis de severidade personalizados. Com base nesses parâmetros, o sistema emite alertas automáticos, possibilita a seleção de subzonas estratégicas e facilita a designação inteligente de agentes de mobilidade para cada área. A solução é complementada por um dashboard interativo, que oferece uma visão consolidada e em tempo real de todos os indicadores de desempenho, padrões de tráfego e métricas dos agentes. Através deste painel, os gestores podem tomar decisões ágeis e embasadas em dados, elevando a eficiência operacional e a qualidade do gerenciamento do trânsito na cidade.

→ [Voltar ao topo](#denarius-data)

---

<span id="backlog-do-produto">

## 📋 Backlog do Produto

OBS: Foram necessárias alterações. Os user stories com * (asterisco) foram criados no planejamento da sprint 3, devido à mudanças no escopo (49 horas) e user stories com ~ (til) foram removidos por incapacidade de atender no prazo e / ou mudanças no escopo (70 horas)

| Rank | Prioridade | User Story | Story Points | Sprint |
|-|-|-|-|-|
| 1 | 🔴 Alta | Como gestor, quero informações sobre o trânsito em forma de dashboards, gráficos e tabelas para auxiliar minha tomada de decisão na diminuição de trânsito | 48 | 1 |
| 2 | 🔴 Alta | Como usuário da plataforma, quero um mapa na tela inicial, que tenha as divisões das zonas da cidade de São José dos Campos, para que eu possa ter uma visão detalhada dos locais que o sistema possui informação | 30 | 1 |
| 3 | 🔴 Alta | Como usuário publico ou como agente, quero uma tela com a documentação dos indicadores para saber o que está sendo avaliado na exibição do mapa da cidade | 42 | 1 |
| 4 | 🔴 Alta * | Como cliente, quero que cada permissão de usuário (gestor, agente e público) tenham acessos diferentes à cada funcionalidade | 26 | 3 |
| 5 | 🟡 Média ~ | Como gestor, quero que a tela de documentação dos indicadores (rank 3) ofereça a possibilidade de adicionar, editar e deletar os indicadores, para que eu tenha controle sobre o monitoramento do trânsito da cidade | 22 | 1 |
| 6 | 🟡 Média ~ | Como gestor, quero ter a possibilidade de alterar as definições dos níveis referentes a um indicador sem modificar a quantidade de níveis existentes, para que o disparo de alertas, que dependem desses níveis, ocorram em momentos controlados | 12 | 2 |
| 7 | 🟡 Média | Como gestor, quero poder associar um usuário agente a uma zona ou usuário gestor a uma zona, para que recebam informações específicas e centralizadas para atuar | 16 | 2 |
| 8 | 🟡 Média | Como agente e como gestor, quero receber alertas quando houver mudança nos níveis de qualquer indicador, para que eu tenha noção de quando o trânsito piorar e possa tomar medidas para solucionar o problema | 39 | 2 |
| 9 | 🟡 Média | Como gestor, quero que as zonas tenham informações das principais vias demarcadas e que apresentem o congestionamento dessa via, para que eu possa atuar de forma mais rápida e precisa em pontos críticos da cidade | 20 | 2 |
| 10 | 🟡 Média | Como gestor, quero poder criar “causas raíz” para alertas disparados e poder criar protocolos para essas “causas raíz”, para que o agente tenha uma orientação de como resolver os alertas que surgirem | 18 | 2 |
| 11 | 🟡 Média | Como agente, quero poder visualizar um alerta específico, para que possa documentar informações sobre este alerta, obter informações sobre como resolver o problema que gerou o alerta e finalizá-lo | 33 | 3 |
| 12 | 🟡 Média * | Como agente e como gestor, quero poder visualizar todos os alertas disponíveis na base | 16 | 3 |
| 13 | 🟡 Média * | Como gestor, quero poder visualizar e manipular todos os usuários disponíveis na base | 7 | 3 |
| 14 | 🟢 Baixa | Como gestor, quero ter logs dos alertas gerados, para registro de auditoria e estudo de histórico do comportamento do trânsito | 6 | 3 |
| 15 | 🟢 Baixa ~ | Como gestor, quero um chat interno no produto para que eu possa consultar informações que estão no banco de forma simplificada | 42 | 3 |

<br />

<details>
    <summary>User Stories originais</summary>
    <br />
    
| Rank | Prioridade | User Story | Story Points | Sprint |
|-|-|-|-|-|
| 1 | 🔴 Alta | Como gestor, quero informações sobre o trânsito em forma de dashboards, gráficos e tabelas para auxiliar minha tomada de decisão na diminuição de trânsito | 48 | 1 |
| 2 | 🔴 Alta | Como usuário da plataforma, quero um mapa na tela inicial, que tenha as divisões das zonas da cidade de São José dos Campos, para que eu possa ter uma visão detalhada dos locais que o sistema possui informação | 30 | 1 |
| 3 | 🔴 Alta | Como usuário publico ou como agente, quero uma tela com a documentação dos indicadores para saber o que está sendo avaliado na exibição do mapa da cidade | 42 | 1 |
| 4 | 🟡 Média | Como gestor, quero que a tela de documentação dos indicadores (rank 3) ofereça a possibilidade de adicionar, editar e deletar os indicadores, para que eu tenha controle sobre o monitoramento do trânsito da cidade | 22 | 1 |
| 5 | 🟡 Média | Como gestor, quero ter a possibilidade de alterar as definições dos níveis referentes a um indicador sem modificar a quantidade de níveis existentes, para que o disparo de alertas, que dependem desses níveis, ocorram em momentos controlados | 12 | 2 |
| 6 | 🟡 Média | Como gestor, quero poder associar um usuário agente a uma zona ou usuário gestor a uma zona, para que recebam informações específicas e centralizadas para atuar | 16 | 2 |
| 7 | 🟡 Média | Como agente e como gestor, quero receber alertas quando houver mudança nos níveis de qualquer indicador, para que eu tenha noção de quando o trânsito piorar e possa tomar medidas para solucionar o problema | 39 | 2 |
| 8 | 🟡 Média | Como gestor, quero que as zonas tenham informações das principais vias demarcadas e que apresentem o congestionamento dessa via, para que eu possa atuar de forma mais rápida e precisa em pontos críticos da cidade | 20 | 2 |
| 9 | 🟡 Média | Como gestor, quero poder criar “causas raíz” para alertas disparados e poder criar protocolos para essas “causas raíz”, para que o agente tenha uma orientação de como resolver os alertas que surgirem | 18 | 2 |
| 10 | 🟡 Média | Como agente, quero poder visualizar um alerta específico, para que possa documentar informações sobre este alerta, obter informações sobre como resolver o problema que gerou o alerta e finalizá-lo | 33 | 3 |
| 11 | 🟢 Baixa | Como gestor, quero ter logs dos alertas gerados, para registro de auditoria e estudo de histórico do comportamento do trânsito | 6 | 3 |
| 12 | 🟢 Baixa | Como gestor, quero um chat interno no produto para que eu possa consultar informações que estão no banco de forma simplificada | 42 | 3 |

</details>

→ [Voltar ao topo](#denarius-data)

---

<span id="dor">

## 🏃‍  DoR - Definition of Ready
- User Stories com Critérios de Aceitação
- Subtarefas divididas a partir das US
- Design no Figma
- Modelagem do Banco de Dados
- Diagrama de Rotas
- Banco de Dados Vetorizado do Cliente

<span id="dod">

## 🏆 DoD - Definition of Done
- Manual de Instalação
- Manual de Usuário
- Documentação da API (Application Programming Interface)
- Código completo
- Vídeos de cada etapa de entrega

→ [Voltar ao topo](#denarius-data)

---

## 📅 Cronograma de Sprints

<span id="cronograma-de-sprints">

| Sprint | Período | Histórico |
|-|-|-|
| SPRINT 1 | 08/09 - 28/09 | [Sprint 1 Docs](https://github.com/DenariusData/API-4SEM/blob/main/docs/processo/sprints/sprint-1/README.md) |
| SPRINT 2 | 06/10 - 26/10 | [Sprint 2 Docs](https://github.com/DenariusData/API-4SEM/blob/main/docs/processo/sprints/sprint-2/README.md) |
| SPRINT 3 | 03/11 - 23/11 | [Sprint 3 Docs](https://github.com/DenariusData/API-4SEM/blob/main/docs/processo/sprints/sprint-3/README.md) |

→ [Voltar ao topo](#denarius-data)

---

<span id="tecnologias">

## 💻 Tecnologias

<p align="center">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-orange?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-CED4DA?style=for-the-badge&logo=visual-studio-code&logoColor=0078D4" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Docs-CED4DA?style=for-the-badge&logo=google-docs&logoColor=0D96F6" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
</p>

→ [Voltar ao topo](#denarius-data)

---

<span id="manual-de-instalacao">

## 📖 Manual de instalação

Acesso ao manual pelo [Link](https://github.com/DenariusData/API-4SEM/blob/main/docs/install/README.md)
<br />

→ [Voltar ao topo](#denarius-data)

---

<span id="manual-do-usuario">

## 📘 Manual do usuário

Acesso ao manual pelo [Link](https://drive.google.com/file/d/1L-FXcJWop9PP2Nl430whKPjNdSdH5czI/view?usp=sharing)
<br />

→ [Voltar ao topo](#denarius-data)

---

<span id="documentacao-api">

## 📓 Documentação API

Acessar à documentação Swagger pelo [Link](https://drive.google.com/drive/folders/1cTevsjRi3AkroBniEprjlUZcLx0zNM3g?usp=sharing)

→ [Voltar ao topo](#denarius-data)

---

<span id="modelagem-de-banco-de-dados">

## 🖥️ Modelagem de Banco de Dados

<img alt="modelagem-banco" src="./docs/media/modelagem-banco-de-dados.png" />

→ [Voltar ao topo](#denarius-data)

---

<span id="equipe">

## :busts_in_silhouette: Equipe

<div align="center">

|    Função     | Nome                  | LinkedIn & GitHub |
|---------------|-----------------------|-------------------|
| Product Owner | Augusto Piatto        | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/augusto-piatto/) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/augustopiatto) |
| Scrum Master  | Beatriz Sthefanny     | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/beatriz-santos-0b6773220/) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/BeatrizSantos00) |
| Dev Team      | Caio Osorio           | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/caio-o-a67224200/) [![Github](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/User-Business) |
| Dev Team      | Davi Soares           | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/dsf21/) [![Github](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/DaviSFS21) |
| Dev Team      | João Paulista         | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joaopaulista/) [![Github](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/joaopaulista) |
| Dev Team      | Rafael Slivka         | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-lopes-slivka-07753326a/) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/rafaslivka) |
| Dev Team      | Tiago Bernardo        | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/tiagobernardosantos/) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/TiagoBernardoSantos) |
| Dev Team      | Tiago Torres          | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/tiago-torres-dos-reis/) [![Github](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/TiagoTReis) |
| Dev Team      | Victor Ryan           | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/victor-ryan-51738b261) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/yzvictorr) |

</div>

→ [Voltar ao topo](#denarius-data)
