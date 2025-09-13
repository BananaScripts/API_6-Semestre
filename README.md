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

# 👋 Hello! Nós somos o grupo BananaScript
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
- **Frontend:** [https://github.com/BananaScripts/API_6-Semester-Frontend](https://github.com/BananaScripts/API_6-Semester-Frontend)  
- **Backend:** [https://github.com/BananaScripts/API_6-Semester-Backend](https://github.com/BananaScripts/API_6-Semester-Backend)  

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
| Sprint 01 | 08.09.2025 - 28.09.2025 | 🟡 |
| Sprint 02 | 06.10.2025 - 26.10.2025 | 🔜 |
| Sprint 03 | 03.11.2025 - 23.11.2025 | 🔜 |
| Feira de Soluções | 29.11.2025 | 🔜 |

---

## MVPs (Minimum Viable Product)

- **Sprint 01 (08.09 - 28.09):** Ingestão de dados via CSV e envio por e-mail.  
- **Sprint 02 (06.10 - 26.10):** Chat com IA conectado ao SQL (consulta em linguagem natural).  
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

## Product Backlog 📖
| ID | Requisitos | Item |
|----|------------|------|
| BCK_1 | RF_1, RF_2 | Importar, tratar e armazenar dados em SQL |
| BCK_2 | RF_3, RNF_2 | Sistema de login e autenticação segura |
| BCK_3 | RF_4, RNF_6 | Interface responsiva (mobile + web) |
| BCK_4 | RF_5 | Chat integrado com GPT/LLM e SQL |
| BCK_5 | RF_6 | Resumos textuais automáticos |
| BCK_6 | RF_7 | Envio de relatórios por e-mail |
| BCK_7 | RNF_3 | Deploy em nuvem (AWS Academy) |
| BCK_8 | RNF_4 | Documentação completa |

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
- Importar e tratar CSV  
- Criar banco SQL e carregar dados  
- Exportar relatórios em CSV  
- Enviar CSV por e-mail  
- Autenticação (login + JWT)  
- Layout responsivo (mobile)  

### Sprint 02 | 06.10 - 26.10
- Implementar motor GPT/LLM  
- Criar API para conectar GPT ao SQL  
- Conectar chat à API  
- Tela de chat com histórico  

### Sprint 03 | 03.11 - 23.11
- Resumos textuais automáticos  
- Boletins adaptados ao modelo DomRock  
- Pipeline completo CSV → SQL → Chat → Resumos  
- Deploy em AWS  
- Tela de resumos  
- Documentação (técnica + usuário)  

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

- **Wiki:** [📂 Documentação do Projeto](https://github.com/BananaScripts/API_6-Semester/wiki)  

📊 Arquitetura do Sistema:  
<img src="./Docs/ArquiteturaDoSistema.png)" width="1000"/>  

---

<span id="equipe">

## 👨‍💻 Equipe  

| Nome | LinkedIn | Github |
|------|----------|--------|
| Bruno Fernandes | [LinkedIn](https://www.linkedin.com/in/bruno-campos-97560b231/) | [GitHub](https://github.com/BrunoFerCam) |
| Douglas Medeiros | [LinkedIn](https://www.linkedin.com/in/douglas-ferrini-medeiros-02b735270) | [GitHub](https://github.com/DouglasMedeiros1) |
| Kauê Riki | [LinkedIn](https://www.linkedin.com/in/kau%C3%AA-riki-70b518273/) | [GitHub](https://github.com/kaueriki) |
| Miguel Conde | [LinkedIn](https://www.linkedin.com/in/miguel-conde-santos-a67313271/) | [GitHub](https://github.com/miguelcondesantos) |
| Antonio Alexandre | [LinkedIn](https://www.linkedin.com/in/antonio-nepomuceno/) | [GitHub](https://github.com/Nepoun) |

---

> Instituição: Fatec São José dos Campos - Prof. Jessen Vidal  
> Curso: Desenvolvimento de Software Multiplataforma / 6º Semestre  

<br>

<a href="#inicio">⬆️ Voltar ao início</a>
