<br id="inicio">

<h1 align="center">API 2025.2 - Banana Script</h1>
 <p align="center">
     <a href="#sobre">Sobre</a> •
     <a href="#tecnologias">Ferramentas e Tecnologias</a> •
     <a href="#entregas">Entregas</a> • 
     <a href="#backlog">Backlogs e User Stories</a> •
     <a href="#documentacao">Documentação</a> •
     <a href="#equipe">Equipe</a> 
</p>

# 👋 Olá! Nós somos o grupo BananaScript
Nós somos estudantes da <a href='https://fatecsjc-prd.azurewebsites.net/'>FATEC de São José dos Campos</a> e estamos no 6º semestre de Desenvolvimento de Software Multiplataforma.

<span id="sobre">

## Sobre o projeto 📊💬
Empresas que lidam com **grande volume de dados** muitas vezes enfrentam dificuldades em transformar essa informação em **insights de negócio ágeis e acessíveis**.  

O cliente **DomRock** nos propôs o desafio de criar um sistema capaz de:
- Ingerir dados via CSV, tratar e armazenar em SQL.  
- Oferecer um **chat inteligente** para consultas em linguagem natural usando **LLM (GPT/Gemini)**.  
- Gerar **resumos executivos automáticos (boletins)** com insights sobre vendas e estoque.  
- Disponibilizar acesso **via web e mobile**, com deploy em **AWS**.  

O sistema busca democratizar o acesso aos dados de negócio, garantindo que analistas e gestores consigam extrair informações de maneira rápida e prática.

---

## 🔗 Links dos Repositórios
- **Frontend:** [[https://github.com/BananaScripts/API_6-Semester-Frontend](https://github.com/BananaScripts/API_6-Semestre-Frontend-Web)]  
- **Backend:** [https://github.com/BananaScripts/API_6-Semestre-Backend](https://github.com/BananaScripts/API_6-Semestre-Backend)]

📌 **Status do projeto:** 🟢 Em desenvolvimento

---

<span id="tecnologias">

## Ferramentas e Tecnologias 

---

<span id="entregas">

## 📅 Entregas  

| Período | Data | Status  |
|---------|------|---------|
| Kickoff | 25.08.2025 - 07.09.2025 | ✅ |
| Sprint 01 | 08.09.2025 - 28.09.2025 | ✅ |
| Sprint 02 | 06.10.2025 - 26.10.2025 | 🟡 |
| Sprint 03 | 03.11.2025 - 23.11.2025 | 🔜 |
| Feira de Soluções | 29.11.2025 | 🔜 |

---

## MVPs (Minimum Viable Product)

- **Sprint 01 (08.09 - 28.09):** Ingestão de dados via CSV e envio por e-mail.  
- **Sprint 02 (06.10 - 26.10):** Busca semântica que retorna respostas em linguagem natural
- **Sprint 03 (03.11 - 23.11):** Resumos automáticos (boletins), refinamentos, deploy em AWS e documentação final.  

---

<span id="backlog">

## 📌 Requisitos  

### Requisitos Funcionais
| ID | Descrição |
|----|-----------|
| RF_1 | Importar e tratar arquivos CSV de vendas e estoque |
| RF_2 | Armazenar dados tratados em banco SQL |
| RF_3 | Permitir login/autenticação de usuários |
| RF_4 | Permitir acesso via mobile (responsividade) |
| RF_5 | Implementar chat com GPT conectado ao SQL |
| RF_6 | Gerar resumos textuais automáticos a partir do SQL |
| RF_7 | Disponibilizar arquivos com os dados e envio por e-mail |

### Requisitos Não Funcionais
| ID | Descrição |
|----|-----------|
| RNF_1 | Utilizar SQL para armazenamento centralizado |
| RNF_2 | Autenticação segura com JWT |
| RNF_3 | Deploy em nuvem (AWS Academy) |
| RNF_4 | Documentar o sistema (manual técnico + usuário) |
| RNF_5 | Garantir desempenho e tempo de resposta adequado |
| RNF_6 | Interface responsiva web e mobile |

---

## User Stories 📖
| ID | User Story |
|----|------------|
| US_1 | Eu, como analista, quero importar um CSV e armazenar em SQL para centralizar os dados. |
| US_2 | Eu, como usuário, quero logar no sistema com segurança para acessar minhas informações. |
| US_3 | Eu, como gestor, quero conversar com o sistema em linguagem natural (chat GPT) para tirar dúvidas rápidas. |
| US_4 | Eu, como gestor, quero receber resumos executivos automáticos sobre vendas e estoque. |
| US_5 | Eu, como gestor, quero acessar o sistema em dispositivos móveis para usá-lo fora do escritório. |
| US_6 | Eu, como administrador, quero receber resumos por e-mail para acompanhar resultados. |
| US_7 | Eu, como cliente/professor, quero documentação clara para instalar, rodar e avaliar o sistema. |

---

<span id="sprints">

## 📋 Tarefas das Sprints  

### Sprint 01 | 08.09 - 28.09 

| Tarefa | Descrição |
|-----------------------|---------------------------------------------|
| Importar e tratar CSV | Criar rotina para carregar dados no sistema |
| Tratar e normalizar dados  | Padronizar datas, corrigir erros e duplicados |
| Criar banco SQL e carregar dados | Organizar dados em tabelas |
| Desenvolver FrontEnd | Criar telas e visual para ser apresentado ao cliente |
| Gerar relatórios em arquivo CSV | Funcionalidade de enviar o arquivo gerado em csv por email |
| Enviar CSV por email | Criar a funcionalidade de criar arquivos em csv dos dados tratados |
| Implementar autenticação (login/senha) | Usuários acessam sistema com segurança |
| Tela de login | Interface para entrada no sistema |
| Segurança do login com tokens | Implementar autenticação com JWT ou similar, garantindo sessão segura. |
| Layout responsivo (mobile) | Garantir funcionamento em celular |

### Sprint 02 | 06.10 - 26.10

| Tarefa | Descrição |
|-----------------------|---------------------------------------------|
| Implementar motor GPT/LLM para consultas | Buscas semânticas que vai entender perguntas em linguagem natural e vai converter em consultas |
| Criar API para conectar GPT ao SQL  | API que envia perguntas e retorna respostas |
| Conectar chat à API GPT | Front envia pergunta, back retorna resposta |
| Tela de chat | Tela com campo de texto, botão enviar e histórico de mensagens. Exatament como um chat |
| Tela de chat (Mobile) | Garantir funcionamento do chat Mobile |

### Sprint 03 | 03.11 - 23.11

| Tarefa | Descrição |
|-----------------------|---------------------------------------------|
| Gerar resumos textuais automáticos | Geração de texto automática. Banco de dados -> Resumos executivos |
| Resumos baseados em SQL| Resumos devem puxar informações direto do banco, nunca de CSV cru. |
| Adaptar boletins ao roteiro da Dom Rock | Ajustar formato conforme modelo do cliente |
| Pipeline completo integrado | Fluxo: CSV → SQL →  Chat + Resumos |
| Hospedar em AWS | Deploy completo do sistema em nuvem |
| Garantir usabilidade mobile | Ajustar para uso confortável em celular |
| Tela de resumos | Página clara e organizada com resumos |
| Documentação | Documentação completa do produto |
| Manual de Instalação | Guia técnico para rodar o sistema |
| Manual do Usuário | Guia prático de uso do sistema |

---

## ✅ DoR e DoD  

| DoR (Definition of Ready) | DoD (Definition of Done) |
|---------------------------|--------------------------|
| User stories e tasks claras e descritas | Funcionalidade integrada na branch *development* via Pull Request |
| Protótipos e arquitetura definidos antes da task | Funcionalidade implementada e testada |
| Dependências disponíveis para execução | Não deve quebrar funcionalidades existentes |

---

<span id="documentacao">

## 📄 Documentação  

- **Wiki:** [📂 Documentação do Projeto](https://github.com/BananaScripts/API_6-Semestre/wiki)

📊 **Arquitetura do Sistema:**  
<img src="https://raw.githubusercontent.com/BananaScripts/API_6-Semestre/main/Docs/ArquiteturaDoSistema.png" width="1000"/>

---

<span id="equipe">

## 👨‍💻 Equipe  

| Nome | LinkedIn | Github |
|------|----------|--------|
| Douglas Medeiros | [LinkedIn](https://www.linkedin.com/in/douglas-ferrini-medeiros-02b735270) | [GitHub](https://github.com/DouglasMedeiros1) |
| Kauê Riki | [LinkedIn](https://www.linkedin.com/in/kau%C3%AA-riki-70b518273/) | [GitHub](https://github.com/kaueriki) |
| Miguel Conde | [LinkedIn](https://www.linkedin.com/in/miguel-conde-santos-a67313271/) | [GitHub](https://github.com/miguelcondesantos) |
| Antonio Alexandre | [LinkedIn](https://www.linkedin.com/in/antonio-nepomuceno/) | [GitHub](https://github.com/Nepoun) |

---

> Instituição: Fatec São José dos Campos - Prof. Jessen Vidal  
> Curso: Desenvolvimento de Software Multiplataforma / 6º Semestre  

<br>

<a href="#inicio">⬆️ Voltar ao início</a>
