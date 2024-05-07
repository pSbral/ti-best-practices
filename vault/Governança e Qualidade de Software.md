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

### Stakeholder
Funciona como o inicio da requisição dos recursos do sistema, é quem determina quais operações são necessárias ou não.

O stakeholder te fornece uma diretriz (driver)
Associa o Stakeholder com as diretrizes
Identifica os objetivos/goals
Conectar os princípios/principles referentes aos objetivos
determinar os requirimentos/requirements

## Arquitetura de Negócio
---
Identifica processos que estarão presentes na área de negócios do projeto.

| Tipo                  | Descrição                                                   |
| --------------------- | ----------------------------------------------------------- |
| Business Process      | Processo do negócio determinado pelos requisitos do sistema |
| Business Function     | Funções exercidas obrigatoriamente ou opcionalmente         |
| Business Actor        | Funcionário que executa os processos do sistema             |
| Business Role         | Papéis exercidos por um ou mais funcionários do sistema     |
| Application Component | Componente front ou back da aplicação                       |
| Application Interface | Interface gráfica de um ou mais componentes                 |
| Data Object           |                                                             |

business process. Um processo é um conjunto de atividades que quando executados em sequencia resultam em um objetivo em comum. Business processes podem ser compostos ou agregar Business Functions.

Processos podem/devem estar associados a uma Location, que identifica a região geográfica que o processo será executando, permitindo a determinação de propriedades de redes e desenvolvimento de interfaces para gerenciamento do sistema

Product seria um "*produto*" ou resultado de uma ou mais operações dentro do sistema.

Business Actor é um a pessoa na empresa que executa um processo e/ou possui um cargo. Business Podem possuir um ou mais papéis dentro do sistema, que define o *perfil de acesso* do usuário, esses papéis são identificados pelos Business Roles.

Também é possível identificar componentes da aplicação e suas interfaces.
