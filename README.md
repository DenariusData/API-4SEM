IMAGEM TO DO

<br id="topo">
<p align="center">
    <a href="#sobre">Sobre</a>  |  
    <a href="#backlogs--user-stories">Backlogs & User Stories</a>  |  
    <a href="#protótipo--documentação">Protótipo & Documentação</a>  |  
    <a href="#tecnologias">Tecnologias</a>  |  
    <a href="#equipe">Equipe</a>
</p>

<span id="sobre">

## :bookmark_tabs: Sobre o projeto

A partir da apresentação do desafio enfrentado pela empresa parceira, a solução desenvolvida se configura em um sistema de alerta através do monitoramente do trânsito de São José dos Campos por controle de radares. O sistema permite o cadastro de critérios, níveis de critério, emissão de alertas com base nos critérios, escolha de subzonas e alocação de agentes de mobilidade para cada área.

Conta com um dashboard interativo, que oferece uma visão detalhada de todos os indicadores selecionados, facilitando a análise e o acompanhamento dos dados relacionados à gestão do trânsito e de agentes de mobilidade. Através desse painel, os administradores podem tomar decisões com base em métricas, padrões e indicadores relevantes ao desempenho.

> _Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos_

:pushpin: **Status do Projeto:** ✔️ Iniciado

### 🏁 Entregas de Sprints

Cada entrega foi realizada a partir da criação de uma **tag** em cada repositório (Backend, Frontend e Docs), além da criação de uma branch neste repositório com um relatório completo de tudo o que foi desenvolvido naquela sprint. Observe a relação a seguir:

| Sprint | Previsão   | Status         | Histórico           |
|--------|------------|----------------|---------------------|
| 01     | 08/09/2025 | ✔️ Iniciado     | [ver relatório TO DO]()   |
| 02     | 06/10/2025 | ✖️ Não iniciado | [ver relatório TO DO]()   |
| 03     | 03/11/2025 | ✖️ Não iniciado | [ver relatório TO DO]()   |

### :clapper: Apresentação Final

Confira a seguir uma demonstração das funcionalidades para cada tipo de usuário do sistema:

<details>
   <summary>TO DO</summary>
   <div align="center">
      <img src="" alt="" />
   </div>
</details>

→ [Voltar ao topo](#topo)

<span id="backlogs--user-stories">

## :clipboard: Requisitos do Sistema

<details>
<summary>Requisitos Funcionais e Não Funcionais</summary>

<br>

| Nº Requisito | Descrição                                  | Tipo                |
|--------------|--------------------------------------------|---------------------|
| RF1          |  | Funcional           |
| RNF1         |                            | Não Funcional       |

</details>

## :dart: Backlogs & DoD e DoR

<details>
<summary>Backlog com User Stories</summary>

<br>

| Rank | Prioridade | User Story | Estimativa | Sprint |
|------|---------------------|------------|------------|--------|
| 1    |     Alta             | "Eu como gestor desejo que tenha bem definido os critérios de mobilidade  para que eu possa visualizar em que situação se encontra um indicador para que eu possa determinar o nível que se encontra uma área" | 1 | 1 | 
| 2 | Alta                | "Eu como gestor desejo que tenha bem definido os níveis de alerta de acordo com os critérios de mobilidade para que eu possa determinar qual nível  se encontra a área para caso tenha algum problema seja possível assim exibir o protocolo adequado definido pela prefeitura " | 3 |1 |  
| 3  | Média                 |"Eu como gestor do sistema quero que tenha uma página mostrando os níveis de acordo com os critérios de mobilidade para que eu possa visualizar em qual nível se encontram as áreas." | 5 | 1 |  
| 4  | Média                 |"Eu como Agente de Mobilidade e Gestor do sistema quero que seja possível visualizar em uma página 1 exemplo de dashboard dinâmico para mostrar os principais corredores da cidade pré-definidos sendo eles R. Bacabal, Av. Cassiano Ricardo e Av. Dr. Nélson d'Ávila , para que eu possa realizar análise de qual corredor é mais movimentado" | 5 |1 |  
| 5  | Baixa                 |"Eu como população quero que seja possível visualizar em uma página um mapa da cidade contendo os níveis dos indicadores de cada área para que eu possa entender em que situação se encontra a área desejada "| 8 | 1 |  
| 6  | Baixa                 |"Eu como gestor do sistema desejo popular gráficos pré-definidos como gráfico de barra, gráfico de pizza e gráfico de dispersão passando os filtros que desejo para que eu possa ter a liberdade de escolher os gráficos e as informações que serão filtradas"  | 13 | 2 |  
| 7  | Alta                 |"Eu enquanto Agente de mobilidade e Gestor do sistema quero que seja possível receber os alertas para que possam ser investigados e posteriormente serem exibidos os protocolos adequados definidos pela prefeitura "  | 8 | 2 |  
| 8  | Baixa                 |"Eu enquanto gestor do sistema quero que tenha um chat na tela onde seja possível eu fazer perguntas direto para meus dados do banco de dados em linguagem natural e que ele me retorne a resposta em linguagem natural para que possa obter análises avançadas pela IA."  | 8 | 3 |  
| 9  | Alta                 | "Eu como gestor do sistema desejo que tenha os seguintes níveis de acesso: usuário geral(sem login), agentes de mobilidade e gestores ambos contendo login, para que no sistema haja uma segurança em relação aos dados que cada grupo poderá acessar"| 13 | 3 |  
# DoR(Definition of Ready)
| US_ID | Resumo da User Story | Título/Valor claro Story | Critérios de Aceitação | Regras de Negócio |
|------|-----------------------|--------------------------|------------------------|-------------------|
| 1 | "Eu como gestor desejo que tenha bem definido os critérios de mobilidade para que eu possa visulizar em que situação se encontra um indicador para que eu possa determinar o nível que se encontra uma área" | Critérios de mobilidade definidos | • Existe um documento com os critérios de mobilidade.<br>• Cada critério possui breve descrição.<br>• Os critérios permitem determinar a situação de cada indicador e, consequentemente, o nível da área. | • Os critérios são a base dos indicadores. |
| 2 | "Eu como gestor desejo que tenha bem definido os níveis de alerta de acordo com os critérios de mobilidade para que eu possa determinar qual nível se encontra a área para caso tenha algum problema seja possível assim exibir o protocolo adequado definido pela prefeitura " | Níveis de alerta por critério | • Existe um documento com os níveis de alerta de cada critério, com breve descrição.<br>• Níveis de alerta são editáveis.<br>• Com base no nível, é possível exibir o protocolo adequado definido pela Prefeitura. | • Níveis de alerta baseados nos critérios de mobilidade.<br>• Exibição do protocolo adequado conforme nível. |
| 3 | "Eu como gestor do sistema quero que tenha uma página mostrando os níveis de acordo com os critérios de mobilidade para que eu possa visualizar em qual nível se encontram as áreas." | Página “Níveis” por região | • Há um botão “Níveis”.<br>• Ao acessar, a página exibe os critérios pré-estabelecidos e os respectivos níveis por região. | • Visualização por região conforme critérios pré-estabelecidos. |
| 4 | "Eu como Agente de Mobilidade e Gestor do sistema quero que seja possível visualizar em uma página 1 exemplo de dashboard dinâmico para mostrar os principais corredores da cidade pré-definidos sendo eles R. Bacabal, Av. Cassiano Ricardo e Av. Dr. Nélson d'Ávila , para que eu possa realizar análise de qual corredor é mais movimentado" | Dashboard dos corredores principais | • Na página principal há um botão que leva ao dashboard.<br>• Ao acessar, o dashboard exibe os três corredores pré-definidos (R. Bacabal, Av. Cassiano Ricardo, Av. Dr. Nélson d’Ávila). | • Dashboard dinâmico de exemplo com os três corredores pré-definidos. |
| 5 | "Eu como população quero que seja possível visualizar em uma página um mapa da cidade contendo os níveis dos indicadores de cada área para que eu possa entender em que situação se encontra a área desejada " | Mapa público com níveis por área | • Ao entrar no sistema, o mapa da cidade carrega exibindo os níveis por área.<br>• Acesso sem autenticação (público). | • Página pública (sem login).<br>• Mapa exibe níveis dos indicadores por área. |
| 6 | "Eu como gestor do sistema desejo popular gráficos pré-definidos como gráfico de barra, gráfico de pizza e gráfico de dispersão passando os filtros que desejo para que eu possa ter a liberdade de escolher os gráficos e as informações que serão filtradas" | Gráficos pré-definidos com filtros | • Interface permite selecionar filtros e o tipo de gráfico (barra, pizza, dispersão).<br>• Ao confirmar, os gráficos são exibidos com os dados correspondentes. | • Tipos de gráfico: barra, pizza e dispersão.<br>• Filtros escolhidos pelo usuário. |
| 7 | "Eu enquanto Agente de mobilidade e Gestor do sistema quero que seja possível receber os alertas para que possam ser investigados e posteriormente serem exibidos os protocolos adequados definidos pela prefeitura " | Recebimento e gestão de alertas | • Quando ocorrerem condições que gerem alerta, eles são exibidos no sistema.<br>• É possível abrir detalhes, registrar a investigação e visualizar o “Protocolo recomendado”. | • Alertas alinhados aos níveis definidos.<br>• Exibição de protocolos definidos pela Prefeitura. |
| 8 | "Eu enquanto gestor do sistema quero que tenha um chat na tela onde seja possível eu fazer perguntas direto para meus dados do banco de dados em linguagem natural e que ele me retorne a resposta em linguagem natural para que possa obter análises avançadas pela IA." | Chat com os dados (LN) | • Campo “Chat com os dados” disponível.<br>• Usuário faz pergunta em linguagem natural sobre os dados do banco.<br>• Sistema responde em linguagem natural com base nos indicadores atuais. | • Perguntas e respostas em linguagem natural sobre os dados do banco. |
| 9 | "Eu como gestor do sistema desejo que tenha os seguintes níveis de acesso: usuário geral(sem login), agentes de mobilidade e gestores ambos contendo login, para que no sistema haja uma segurança em relação aos dados que cada grupo poderá acessar" | Níveis de acesso por perfil | • Ao acessar com cada perfil (usuário geral sem login; agentes/gestores com login), apenas as funcionalidades e dados permitidos ficam disponíveis.<br>• O mapa público permanece acessível sem login. | • Perfis: usuário geral (sem login), agentes e gestores (com login).<br>• Segurança por restrição de funcionalidades/dados por perfil.<br>• Mapa público sem login. |

# DoD(Definition of Done)
| US_ID | Repositório (branch) | Manual do usuário | Como validar |
|-----:|-----------------------|-------------------|--------------|
| 1 | DenariusData/API-4SEM | docs/manual_01.pdf | Documento entregue contendo os critérios de mobilidade e uma breve descrição de cada um. |
| 2 | DenariusData/API-4SEM | docs/manual_02.pdf | Documento entregue com os níveis de alerta por critério e breve descrição; níveis devem ser editáveis. |
| 3 | DenariusData/API-4SEM | docs/manual_03.pdf | A página estará pronta quando houver um botão “Níveis”; ao entrar, será possível ver os critérios pré-estabelecidos e os respectivos níveis por região. |
| 4 | DenariusData/API-4SEM | docs/manual_04.pdf | Na página principal haverá um botão que leva ao dashboard; ao acessá-lo, o dashboard será visualizado normalmente com os três corredores pré-definidos. |
| 5 | DenariusData/API-4SEM | docs/manual_05.pdf | Ao entrar no sistema, o mapa da cidade será carregado exibindo os níveis por área, acessível sem autenticação (público). |
| 6 | DenariusData/API-4SEM | docs/manual_06.pdf | Na interface, será possível selecionar filtros e o tipo de gráfico; ao confirmar, os gráficos serão exibidos com os dados correspondentes. |
| 7 | DenariusData/API-4SEM | docs/manual_07.pdf | Quando ocorrerem condições que gerem alerta, eles serão exibidos no sistema; será possível abrir os detalhes, registrar a investigação e visualizar o “Protocolo recomendado”. |
| 8 | DenariusData/API-4SEM | docs/manual_08.pdf | Haverá um campo “Chat com os dados”; ao perguntar (ex.: “Quais áreas estão no nível mais crítico hoje?”), o sistema responderá com base nos indicadores atuais. |
| 9 | DenariusData/API-4SEM | docs/manual_09.pdf | Ao acessar com cada perfil, somente as funcionalidades e dados permitidos estarão disponíveis; o mapa público permanece acessível sem login. |



</details>

</details>

→ [Voltar ao topo](#topo)

<span id="protótipo--documentação">

## :desktop_computer: Protótipo & Documentação

Como parte do planejamento do projeto foram criados wireframes para idealização do layout, que, ao ser validado pelo cliente, foram aplicados em um protótipo construído no Figma [clique aqui para acessar o figma](https://www.figma.com/design/lk2lV7XpSpoS1hqHCWC5dp/API-4%C2%BA-Semestre?node-id=0-1&t=sugjN9rY1RMcNUL1-1), possibilitando a interação do usuário com a interface.

> 🔗 **Links gerais**  
> - **Documentação do software:** [clique aqui para acessar](https://github.com/DenariusData/API-4SEM/blob/main/docs/install/README.md)  
> - **Manual do usuário:** [clique aqui para acessar](https://github.com/DenariusData/DenariusData-docs/blob/main/Manual%20do%20Usuario.pdf)  
> - **Links para os repositórios criados:**  
>    - **Frontend:** [acessar Denarius-Data-Frontend](https://github.com/DenariusData/API-4SEM-FRONTEND/tree/main)  
>    - **Backend:**  [acessar Denarius-Data-Backend](https://github.com/DenariusData/API-4SEM-BACKEND/tree/main)  
> - **Documentações das APIs:**  
>    - **Documentação Endpoint:** [acessar Swagger](#)  
>    - **Guia de Usuário:** [acessar Guia de usuário](https://github.com/DenariusData/DenariusData-docs/blob/main/Manual%20do%20Usuario.pdf)

→ [Voltar ao topo](#topo)

<span id="tecnologias">

## 🛠️ Tecnologias

As seguintes ferramentas, linguagens, bibliotecas e tecnologias foram usadas na construção do projeto:

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Java](https://img.shields.io/badge/Java-orange?style=for-the-badge&logo=openjdk&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![VS_Code](https://img.shields.io/badge/VS_Code-CED4DA?style=for-the-badge&logo=visual-studio-code&logoColor=0078D4)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Google_Docs](https://img.shields.io/badge/Google%20Docs-CED4DA?style=for-the-badge&logo=google-docs&logoColor=0D96F6)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)


→ [Voltar ao topo](#topo)

<span id="equipe">

## :busts_in_silhouette: Equipe

|    Função     | Nome                  | LinkedIn & GitHub |
|---------------|-----------------------|-------------------|
| Product Owner | Augusto Piatto           | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/augusto-piatto/) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/augustopiatto) |
| Scrum Master  | Beatriz Sthefanny     | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/beatriz-santos-0b6773220/) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/BeatrizSantos00) |
| Dev Team      | Caio Osorio        | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/caio-o-a67224200/) [![Github](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/User-Business) |
| Dev Team      | Davi Soares           | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/dsf21/) [![Github](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/DaviSFS21) |
| Dev Team      | João Paulista         | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joaopaulista/) [![Github](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/joaopaulista) |
| Dev Team      | Rafael Slivka         | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-lopes-slivka-07753326a/) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/rafaslivka) |
| Dev Team      | Tiago Bernardo        | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/tiagobernardosantos/) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/TiagoBernardoSantos) |
| Dev Team      | Tiago Torres          | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/tiago-torres-dos-reis/) [![Github](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/TiagoTReis)
| Dev Team      | Victor Ryan           | [![Linkedin](https://img.shields.io/badge/Linkedin-blue?logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/victor-ryan-51738b261) [![GitHub](https://img.shields.io/badge/GitHub-111217?logo=github&logoColor=white)](https://github.com/yzvictorr) |

→ [Voltar ao topo](#topo)

