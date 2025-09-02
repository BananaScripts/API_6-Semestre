# API_6-Semestre
Neste repositório, estamos armazenando as versões do nosso sexto projeto semestral da faculdade. Nesse semestre, faremos um software Mobile e Web de Insigths para Big Data de Negócios com IA.

# Projeto – Sistema de Relatórios e Chat com GPT 📊💬

## MVPs (Minimum Viable Product)

#### Sprint 01 | 08.09 - 28.09
Ingestão de dados via CSV e enviá-los por email

#### Sprint 02 | 06.10 - 26.10
Implementação do chat com IA conectado ao SQL (consulta em linguagem natural).

#### Sprint 03 | 03.11 - 23.11
Geração de resumos automáticos (boletins), refinamentos, deploy em AWS e documentação final.

---

## Requisitos

### Requisitos Funcionais
| **ID** | **Descrição** |
|--------|---------------|
| RF_1 | Importar e tratar arquivos CSV de vendas e estoque |
| RF_2 | Armazenar dados tratados em banco SQL |
| RF_3 | Permitir login/autenticação de usuários |
| RF_4 | Permitir acesso via mobile (responsividade) |
| RF_5 | Implementar chat com GPT conectado ao SQL |
| RF_6 | Gerar resumos textuais automáticos a partir do SQL |
| RF_7 | Disponibilizar arquivos com os dados  e envio por e-mail |

### Requisitos Não Funcionais
| **ID** | **Descrição** |
|--------|---------------|
| RNF_1 | Utilizar SQL para armazenamento centralizado dos dados |
| RNF_2 | Implementar autenticação segura com JWT |
| RNF_3 | Hospedar a aplicação em nuvem (AWS Academy) |
| RNF_4 | Documentar o sistema (manual técnico + manual do usuário) |
| RNF_5 | Garantir desempenho e tempo de resposta adequado |
| RNF_6 | Interface responsiva para web e mobile |

---

## Product Backlog 📖

| **ID** | **Requisitos** | **Item** |
|--------|----------------|----------|
| BCK_1 | RF_1, RF_2 | Importar, tratar e armazenar dados em SQL |
| BCK_2 | RF_3, RNF_2 | Sistema de login e autenticação segura |
| BCK_3 | RF_4, RNF_6 | Interface responsiva (mobile + web) |
| BCK_4 | RF_5 | Chat integrado com GPT/LLM e SQL |
| BCK_5 | RF_6 | Resumos textuais automáticos a partir do SQL |
| BCK_6 | RF_7 | Resumos acessíveis em tela e enviados por e-mail |
| BCK_7 | RNF_3 | Deploy em nuvem (AWS Academy) |
| BCK_8 | RNF_4 | Documentação completa do produto |

---

## User Stories 📖

| **ID** | **User Story** |
|--------|----------------|
| US_1 | Eu, como analista, quero importar um CSV e armazenar em SQL para centralizar os dados. |
| US_2 | Eu, como usuário, quero logar no sistema com segurança para acessar minhas informações. |
| US_3 | Eu, como gestor, quero conversar com o sistema em linguagem natural (chat GPT) para tirar dúvidas rápidas. |
| US_4 | Eu, como gestor, quero receber resumos executivos automáticos sobre vendas e estoque. |
| US_5 | Eu, como gestor, quero acessar o sistema em dispositivos móveis ppara acessar fora do escritório. |
| US_6 | Eu, como administrador, quero receber resumos por e-mail para acompanhar resultados. |
| US_7 | Eu, como professor/cliente, quero documentação clara para instalar, rodar e avaliar o sistema. |

---

## Tarefas das Sprints

### Sprint 01 | 08.09 - 28.09
| **ID** | **Título** | **Descrição** |
|--------|------------|---------------|
| 1 | Importar CSV do cliente | Criar rotina para carregar dados no sistema |
| 2 | Tratar e normalizar dados | Padronizar datas, corrigir erros e duplicados |
| 3 | Criar banco SQL e carregar dados | Organizar dados em tabelas |
| 4 | Desenvolver FrontEnd | Criar telas e visual para ser apresentado ao cliente |
| 5 | Gerar relatórios em CSV | Criar funcionalidade de exportar dados tratados |
| 6 | Enviar CSV por e-mail | Envio automático de arquivos por e-mail |
| 7 | Implementar autenticação (login/senha) | Usuários acessam sistema com segurança |
| 8 | Tela de login | Interface para entrada no sistema |
| 9 | Segurança do login com tokens | Autenticação com JWT |
| 10 | Layout responsivo (mobile) | Garantir funcionamento em celular |

---

### Sprint 02 | 06.10 - 26.10
| **ID** | **Título** | **Descrição** |
|--------|------------|---------------|
| 11 | Implementar motor GPT/LLM | Configurar modelo para responder em linguagem natural |
| 12 | Criar API para conectar GPT ao SQL | API que envia perguntas e retorna respostas |
| 13 | Conectar chat à API GPT | Integração front-back para perguntas e respostas |
| 14 | Tela de chat | UI com campo de texto e histórico de mensagens |

---

### Sprint 03 | 03.11 - 23.11
| **ID** | **Título** | **Descrição** |
|--------|------------|---------------|
| 15 | Gerar resumos textuais automáticos | Resumir dados em relatórios executivos |
| 16 | Resumos baseados em SQL | Garantir que os resumos puxem direto do banco |
| 17 | Adaptar boletins ao roteiro Dom Rock | Ajustar formato conforme modelo do cliente |
| 18 | Pipeline completo integrado | Fluxo: CSV → SQL → Chat + Resumos |
| 19 | Hospedar em AWS | Deploy completo do sistema em nuvem |
| 20 | Garantir usabilidade mobile | Ajustar chat e interface para celular |
| 21 | Tela de resumos | Página clara e organizada para exibir relatórios |
| 22 | Documentação | Documentação completa do produto |
| 23 | Manual de Instalação | Guia técnico para rodar o sistema |
| 24 | Manual do Usuário | Guia prático de uso do sistema |

---

## DoD e DoR

| DoR (Definition of Ready) | DoD (Definition of Done) |
|---------------------------|--------------------------|
| As tasks e user stories devem estar claras e com descrição. | A funcionalidade deve estar integrada na branch *development* via Pull Request. |
| Protótipos ou arquitetura devem estar definidos antes da task começar. | A funcionalidade deve estar implementada e testada. |
| Dependências para a task devem estar disponíveis. | A funcionalidade não deve quebrar outra já existente. |

