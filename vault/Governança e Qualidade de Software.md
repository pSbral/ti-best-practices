# Visão de Arquitetura
---
A arquitetura do projeto ajuda a identificar os objetivos e processos do sistema de uma maneira mais clara. Projeto desenvolvido com o professor Parducci.

## Arquitetura de Projeto
---
Identifica as necessidades do sistema.

| Tipo        | Descrição                                           |
| ----------- | --------------------------------------------------- |
| Stakeholder | Nódulo que determina todos os processos do sistema. |
| Driver      | Razões centrais pro desenvolvimento do sistema.     |
| Goal        | Objetivos determinados a serem atingidos            |
| Outcome     | Resultado dos objetivos                             |
| Requirement | Requisitos do Sistema baseados nos objetivos        |
| Constraint  | Necessidades dos Requisitos do Sistema              |

A arquitetura do projeto é desenvolvida com os objetivos do **Stakeholder** em mente, onde os mesmos são identificados dentro do projeto como os **Drivers**.

**Goals** são os objetivos do sistema que atendem as requisições do Stakeholder, e ao serem executados irão gerar uma consequência, ou um **Outcome**.

> [!NOTE] Principle
> Princípios são identificados na arquitetura para determinar normas que devem ser atendidas para que o objetivo do sistema possa ser completado.

Por fim os requisitos do sistema são identificados como os **Requirements** do sistema, cada um podendo possuir um ou mais **Constraints**. Requirements e constraints são utilizados pelos engenheiros de software para construir o esqueleto inicial do sistema, e através deles é possível construir a **Arquitetura de Negócio**.

## Arquitetura de Negócio
---
Identifica processos que estarão presentes na área de negócios do projeto.

| Tipo                  | Descrição                                                     |
| --------------------- | ------------------------------------------------------------- |
| Business Process      | Processo do negócio determinado pelos requisitos do sistema   |
| Business Function     | Funções exercidas obrigatoriamente ou opcionalmente           |
| Business Actor        | Funcionário que executa os processos do sistema               |
| Business Role         | Papéis exercidos por um ou mais funcionários do sistema       |
| Application Component | Componente front ou back da aplicação                         |
| Application Interface | Interface gráfica de um ou mais componentes                   |
| Data Object           | Objeto presente dentro do sistema para ser gerado ou acessado |

**Business Processes** são os processos do sistema, um conjunto de atividades que quando executados em sequencia para cumprir um objetivo em comum. Business processes podem ser compostos ou agregar **Business Functions**, funções generalistas que desencadeiam outras funções. **Product** seria um "produto" ou resultado de uma ou mais operações dentro do sistema.

> [!NOTE] Location
> Processos podem/devem estar associados a uma **Location**, que identifica a região geográfica que o processo será executando, permitindo a determinação de propriedades de redes e desenvolvimento de interfaces para gerenciamento do sistema.

**Business Actor** é um a pessoa na empresa que executa um processo e/ou possui um cargo. Esse funcionário pode possuir um ou mais papéis dentro do sistema, que define o *perfil de acesso* do usuário, esses papéis são identificados pelos **Business Roles**.

Também é possível identificar componentes da aplicação e suas interfaces através de **Application Interface** e **Application Components**. Componentes podem interagir com outros componentes através de **Application Interactions** e acessar **Data Objects** dentro do sistema.