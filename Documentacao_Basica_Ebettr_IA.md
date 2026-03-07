# Documentação Básica — Ebettr IA

## Visão Geral

A **Ebettr IA** é uma plataforma para criação e operação de agentes de inteligência artificial baseada em automação utilizando **n8n** como motor de execução.

A plataforma funciona como uma **camada de abstração sobre o n8n**, permitindo que empresas utilizem agentes automatizados sem precisar lidar diretamente com a complexidade técnica dos workflows.

A Ebettr IA é responsável por **garantir a execução completa do workflow de ponta a ponta**, assegurando que as automações funcionem de maneira estável, segura e padronizada.

---

# Filosofia da Plataforma

Um dos princípios da Ebettr IA é **separar o uso da automação da complexidade da sua construção**.

Isso significa que:

* O cliente **não precisa conhecer n8n**
* O cliente **não precisa construir workflows**
* O cliente **utiliza o agente pronto e configurado**

A equipe da **Ebettr IA** é responsável por projetar, criar e manter os workflows que executam os agentes.

Essa abordagem garante:

* maior estabilidade do sistema
* padronização das automações
* redução de erros operacionais
* manutenção centralizada da lógica do agente

---

# Controle dos Workflows

Na arquitetura da Ebettr IA, os **workflows não são editáveis pelo cliente final**.

Os fluxos de automação são desenvolvidos e gerenciados exclusivamente pela equipe da plataforma.

Isso garante que:

* a lógica da automação permaneça consistente
* integrações continuem funcionando corretamente
* alterações indevidas não comprometam o sistema

O cliente interage com o agente através da interface da plataforma, sem necessidade de modificar diretamente os workflows.

---

# Integração com Usuários Avançados

Embora a plataforma abstraia o uso do n8n, a Ebettr IA também permite integração com usuários ou empresas que já utilizam essa tecnologia.

Nesse cenário:

* o cliente pode possuir seus próprios workflows
* esses fluxos podem ser integrados à infraestrutura da Ebettr IA
* a plataforma passa a operar ou executar esses workflows dentro do ambiente gerenciado

Mesmo nesses casos, a execução e o gerenciamento continuam sendo controlados pela infraestrutura da Ebettr IA.

---

# Arquitetura da Plataforma

A Ebettr IA é baseada em três componentes principais:

1. **RAG (Base de Conhecimento)**
2. **Configuração de Agentes**
3. **Gerenciamento de Credenciais**

Esses componentes se conectam diretamente com o **motor de automação n8n**, responsável pela execução dos workflows.

---

# 1. RAG — Base de Conhecimento

O sistema de **RAG (Retrieval Augmented Generation)** representa a base de conhecimento utilizada pelos agentes.

Esse componente permite que os agentes consultem informações relevantes durante a execução das automações.

### Funções

* armazenamento de documentos
* consulta contextual de dados
* suporte à geração de respostas mais precisas
* atualização da base de conhecimento do agente

---

# 2. Configurações do Agente

A plataforma oferece uma interface onde o cliente pode configurar o comportamento do agente.

Essas configurações são feitas por meio de formulários e parâmetros definidos na plataforma.

As informações fornecidas são utilizadas para ajustar o funcionamento dos workflows que executam o agente.

Exemplos de configurações:

* comportamento do agente
* parâmetros de automação
* regras específicas do cliente
* dados de contexto para execução

Essas configurações são enviadas automaticamente para os workflows gerenciados pela plataforma.

---

# 3. Gerenciamento de Credenciais

A Ebettr IA possui um sistema de gerenciamento de credenciais para integração com serviços externos.

### Funcionamento

1. O cliente fornece credenciais através da interface da plataforma.
2. As credenciais são enviadas para os servidores da Ebettr IA.
3. Utilizando a **API do n8n**, essas credenciais são registradas diretamente no ambiente de automação.
4. Os workflows passam a utilizar essas credenciais durante sua execução.

Esse processo permite integrações seguras com APIs e ferramentas externas.

---

# Monitoramento de Execuções

A plataforma permite que o cliente acompanhe o funcionamento dos seus agentes.

Os usuários podem visualizar:

* execuções de workflows
* status das automações
* histórico de execuções
* logs e possíveis erros

Isso oferece transparência sobre como os agentes estão operando.

---

# Papel do n8n na Ebettr IA

O **n8n** atua como o motor de execução das automações.

Ele é responsável por:

* executar workflows
* orquestrar integrações
* processar a lógica operacional dos agentes
* gerenciar automações complexas

A Ebettr IA funciona como uma **camada de controle e gerenciamento sobre essa infraestrutura**, permitindo que os usuários utilizem automação avançada sem precisar operar diretamente a ferramenta.